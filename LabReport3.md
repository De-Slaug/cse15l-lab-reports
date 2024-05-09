* # Part 1 - Bugs:
  * ## The Buggy Code In Question:
    * ![Image](Code.PNG)
  * ## My Failure Inducing Input:
    ```
    public void testReverseInPlace() { 
      int[] input1 = { 1, 2, 3, 4, 5, 6, 7 };
      ArrayExamples.reverseInPlace(input1);
      assertArrayEquals(new int[]{ 7, 6, 5, 4, 3, 2, 1 }, input1)
    }
  * ## My Non-Failure Inducing Input:
    ```
    public void testReverseInPlace() {
      int[] input1 = { 7 };
      ArrayExamples.reverseInPlace(input1);
      assertArrayEquals(new int[]{ 7 }, input1);
	}
  * ## The Symptom:
   * ![Image](symptom.png) 
  * ## The Buggy Code and the Fixed Code:
    * Before (Buggy):
      ```
      static void reverseInPlace(int[] arr) {
        for(int i = 0; i < arr.length; i += 1) {
          arr[i] = arr[arr.length - i - 1];
        }
      }
    * After (Resolved):
      ```
      static void reverseInPlace(int[] arr) {
        int[] temp_array = new int[arr.length];
        for(int i = arr.length - 1, j = 0; i >= 0; i--, j++) {
          temp_array[j] = arr[arr.length - j- 1];
        }

        for (int k = 0; k < arr.length; k++) {
          arr[k] = temp_array[k];
        }
      }
  * ## Reflection:
    I AM REFLECTING I AM REFLECTING I AM REFLECTING 
* # Part 2 - Researching Commands:
  *  Command of Choice: Grep
  *  ![Image](updatedSSHpath.PNG)
  *  ![Image](lr2NoPassword.PNG)
