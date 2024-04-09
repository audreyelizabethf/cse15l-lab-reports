# Lab Report 1 - Remote Access and FileSystem
## `$ cd`
> `$ cd`
> ![Image](Lab1_1.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * There was no output because it goes to the home directory (~).
> * This output is not an error.

> `$ cd ~/lecture1/lecture1/folder`
> ![Image](Lab1_4.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * There was no output because it changes the directory to ~/lecture1/lecture1/folder.
> * This output is not an error.

> `$ cd ~/lecture1/lecture1/Hello.java`
> ![Image](Lab1_5.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because Hello.java is not a directory, therefore I cannot change my working directory using `cd` to Hello.java.
> * No this output is not an error.

## `$ ls`
> `$ ls`
>  ![Image](Lab1_6.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because these are the files and folders within the given path.
> * This output is not an error.

> `$ ls ~/lecture1/lecture1/folder`
> ![Image](Lab1_8.png)
> * **Absolute** path to the working directory **before** the command was run: ~lecture1/lecture1
> * I got this output because myFile.txt is the only file inside the directory ~/lecture1/lecture1/folder
> * This output is not an error

> `$ ls ~/lecture1/lecture1/folder/myFile.txt`
> ![Image](Lab1_9.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because there are no files and folders in the given path.
> * This output is not an error.

## `$ cat`
> `$ cat`
> ![Image](Lab1_7.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because there are no contents in the files given by the path that can be printed by this command.
> * This output is not an error.

> `$ cat ~/lecture1/lecture1/folder`
> ![Image](Lab1_10.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because there is nothing inside this directory that can be printed by this command.
> * This output is not an error.

> `$ cat ~/lecture1/lecture1/folder/myFile.txt`
> ![Image](Lab1_11.png)
> * **Absolute** path to the working directory **before** the command was run: ~/lecture1/lecture1
> * I got this output because "Hello, World!" is the contents of this file.
> * This output is not an error.
