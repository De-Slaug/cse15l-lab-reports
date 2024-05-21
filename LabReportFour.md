* # Lab Report 4 - The Process
  * ## Step One (Four - Log into ieng6)
    * ![Image](SSH.png)
    * Key Strokes: `ssh nmoranbautista@ieng6.ucsd.edu` <`enter`>
  * ## Step Two (Five - Clone your fork of the repository from your Github account (using the SSH URL))
    * ![Image](cloning.png)
    * Key Strokes: `git clone ` <`ctrl + v`> <`enter`>
  * ## Step Three (Six - Run the tests, demonstrating that they fail)
    * ![Image](failedTest.png)
    * Key Strokes: `cd lab7` <`enter`> `bash test.sh` <`enter`>
  * ## Step Four (Seven - Edit the code file to fix the failing test)
    * ![Image](alsoVim.png)
    * ![Image](editCode.png)
    * Key Strokes:  `vim ListExamples.java` <`enter`> `k` `k` `k` `k` `k` `k` `l` `l` `l` `l` `l` `l` `l` `l` `l` `l` `l` `x` `i` `2`<`Esc`> `:wq` <`enter`>
  * ## Step Five (Eight - Run the tests, demonstrating that they now succeed)
    * ![Image](passedTest.png)
    * Key Strokes: `bash test.sh` <`enter`>
  * ## Step Six (Nine - Commit and push the resulting change to your Github account (you can pick any commit message!) )
    * ![Image](pushin.png)
    * Key Strokes: `git add` <`enter`> `git commit` <`enter`> `i` `I think this is the commit message`<`esc`> `:wq` <`enter`> `git push` <`enter`>
