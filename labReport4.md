# Lab Report 4 - Vim

## Step 4 - Log into ieng6
![Image](lr4-1)
![Image](lr4-2)

Keys pressed - `ssh auf001@ieng6.ucsd.edu` `<enter>`

After typing `ssh auf001@ieng6.ucsd.edu` into the terminal and pressing `<enter>` I was then connected to the ieng6 server.

## Step 5 - Clone forked repository
![Image](lr4-3)

Keys pressed - `git clone https://github.com/audreyelizabethf/lab7.git` `<enter>`

Typing `git clone https://github.com/audreyelizabethf/lab7.git` and pressing `<enter>` cloned my forked repository into my workspace.

## Step 6 - Run the tests (failures)
![Image](lr4-4)

Keys pressed - `cd` `<space>` `<enter>`, `Ctrl-C` `Ctrl-V` `<enter>`, `Ctrl-C` `Ctrl-V` <space> `ListExamplesTests` `<enter>`

The first sequence of keys I pressed (`cd` `<space>` `<enter>`) changed my working directory into the `lab7` directory.

For the second sequence of keys I pressed, I tabbed out of VSCode and into the Lab 7 write up where I pressed `Ctrl-C` to copy the command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then tabbed back into VSCode where I pressed `Ctrl-V` to paste the command. I then pressed `<enter>` to compile the file.

For the third secquence of keys I pressed, I repeated the process again by using `Ctrl-C` to copy the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore` from the Lab 7 write up, then used `Ctrl-V` to paste the command into the terminal in VSCode. I then pressed `<space>` and typed out `ListExamplesTests`. Then I pressed `<enter>` to run the tests.

## Step 7 - Fix the failing test
In the terminal:
![Image](lr4-5)

Keys pressed: `vim ListExamples.java` `<enter>`

I typed `vim ListExamples.java` into the terminal and pressed `<enter>` which allowed me to edit the file through the commandline via Vim.

![Image](lr4-6)

Keys pressed: `<shift>-g` `k` `k` `k` `k` `k` `k` `<shift>-6` `l` `l` `l` `l` `l` 'a' `<backspace>` `2` `<esc>` `:wp` `<enter>`

I pressed `<shift>` and `g` at the same time to get a capital `G` which brought be to the bottom of the file in Vim. Then I pressed `k` 6 times to bring my cursor up 6 lines. Then I pressed `<shift>` and `6` to get `^` at the same time which brought me to the first word in the line. Then I pressed `l` 5 times to bring my cursor to the `1` in `index1`. Then I pressed `a` to append to the line and used `<backspace> and pressed `2` to change `index1` to `index2`. To exit vim, I pressed `<esc>` to go into normal mode and pressed `:wp` and `<enter>` to save my changes and exit vim. 

## Step 8 - Run the tests (successes)
![Image](lr4-7)

Keys pressed: `<up>` `<up>` `<up>` `<enter>`, `<up>` `<up>` `<up>` `<enter>`

I pressed the `<up>` arrow key 3 times to get to the 3rd item up in my command history which was `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then I pressed `<enter>` to compile the file. I repeated the process a second time to get the the 3rd item up in my command history which was now `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` then I pressed `<enter>` to run the file.

## Step 9 - Commit and push the changes
![image](lr4-b)

Keys pressed: `git add .` `<enter>`, `git commit -m "bug fix"` `<enter>`, `git push` `<enter>`

`git add .` and pressing `<enter>` adds the changes I made to the files in the `lab7` directory to the "staging area." Then `git commit -m "bug fix"` and pressing `<enter>` commits the changes to the repository. Lastly, `git push` and pressing `<enter>` makes those changes visible on GitHub.

