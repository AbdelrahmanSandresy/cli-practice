# Command Line Practice

## Points to Ponder

*Look through these now and then use them to test yourself after doing the assignment*

* What is the command line?
    It's a built in interface that allows user to interact with the machine with no GUI. User executes commands in the shell
* How do you open it on your computer?
    On MacOs utilize the terminal. in vs code press ^ + shift+ `
* How can you navigate into a particular file directory?
    - Where will `cd .` navigate you to?
        the current directory
    - Where will `cd ..` navigate you to?
        the parent directory fom the current directory. one level above
    - Where will `cd ~` navigate you to?
        user home directory
    - Where will `cd /` navigate you to?
        root directory


* How can you display the name of the directory you are currently in?
    pwd
* How can you display the contents of the directory you are currently in?
    ls      
* How can you create a new directory?
    mkdir <dirName>
* How can you create a new file?
    touch <filename>
* How can you destroy a directory or file?
    for files rm <filename> for dir rm -r <dirname> 
* How can you rename a directory or file?
    mv <old-dir or filename> <new_Name>
## Assignment:

1. Complete this interactive course to get a great handle on the essentials of using a command-line interface and navigating directories - [Terminal Tutor](https://www.terminaltutor.com/)
    Done 

2. Complete the below exercise locally on your own computer.
> Unlike Terminal Tutor, your own local terminal can autocomplete file names based on the directory you are in. For example, if you had a directory structure like:
> ```
> home
> |- essays
> |- documents
> |- doodles
> |- code
>```
> and you were currently at home (`~`) all you would need to type is `e` and then hit tab to autocomplete. If you typed `d` and hi tab it would list the two possible matching options (`documents`, `doodles`) prompting you to type enough for it to know for sure what you mean when you hit tab. Tab autocomplete is a powerful feature when navigating a filesystem through the terminal as it let's you know what is available at any given level and allows you to not have write out entire file/folder names completely. Try to take advantage of it!

## Exercise:

In this exercise you will practice creating files and directories and deleting them.

1. Navigate to your home directory (`~`)
1. Create a new directory in your home directory and  name it `test`
2. Navigate into the `test` directory
3. Create a new file called `test.txt` using the `touch` command
4. Open this file with VSCode (from the command line using `code test.txt`) give it some content, and then save
5. From within the cli, view the contents of the file you just created (`head`, `tail`, `less`)
4. Navigate one level up from the `test` directory to it's parent directory
5. Delete the `test` directory (it contains files now, so you might need to add an option to `rm`!)
