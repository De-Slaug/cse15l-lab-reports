# 1) cd - Changes the directory. 
## A) cd: No Argument
* ![Image](cd no argument.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
  * `cd` with no argument means to go back to the previous directory, similar to `..`. As such, this command took us back to the directory before `lecture1`, that is. It took us to the home directory. In my case: `/c/Users/lonkn/`.
* Was it an error?:
  * It was not an error !
## B) cd: To a Directory
* ![Image](cd path to directory.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
  * This one used `cd` in the most practical way. All it did was move us into the desired directory, in this case: `~/lecture1/messages`.
* Was it an error?:
  * Not an error. 
## C) cd: To a file
* ![Image](cd path to file.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
  * I got this output because the command said to change directories into a file, which is not a directory.   
* Was it an error?:
  * This was an error. `cd messages/en-us.txt` is telling the terminal to change diectories into the file `en-us.txt`, this is an impossible action, and there is no reason for the terminal to be able to resolve this. A file can not contain a file (at least within the realm of what I know now), so you cannot `cd` inside of it. 

# 2) ls - Lists the files in a directory.
## A) ls: No Argument
* ![Image](cd no argument.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:
## B) ls: To a Directory
* ![Image](ls path to directory.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:
## C) ls: To a file
* ![Image](ls path to file.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:

# 3) cat - Concatenates / merges multiple files and the contents thereof.
## A) cat: No Argument
* ![Image](cat no argument.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:
## B) cat: To a Directory
* ![Image](cat path to directory.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:
## C) cat: To a file
* ![Image](cat path to file.PNG) 
* Absolute Path: ![Image](absolutepath.PNG)
* Why did I get this output?:
* Was it an error?:
