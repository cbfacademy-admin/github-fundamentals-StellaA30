## Command Line 

* use `mkdir` to make a new directory and `pwd` to print the current directory
* use `cd` command to change directory 
> 1. `cd` alone can take you back to the home directory
> 2. `cd..` takes you a level up 

* use `touch` command to create a new empty file, for example: `touch README.md` create a new README file

* use `mv [filename] [pathname]` to move a file to a different destination 

* Deleting files and directory
>1. Use the `rm -r {directoryname}` to remove a directory
>2. Use the `rm {filename}` to remove a file

* The `ls` command shows you al the files etc in a directory, i.e., the list of content within a given directory

## Introduction to Git and Github

* Git is a version control system
* GitHub is a cloud based hosting platform for git repositories, version control and collaboration

* Git hasa set of commands to help with version control
>1. `git init` is used to initialise version control in the current working directory on your local computer
>2. `git add` is used for staging, i.e., adding files and changes
    >>* `git add {filename}` add that specified file 
     >>* `git add .` adds all files
>3. `git commit` takes the snapshot of the repository's currently staged changes and commits are always saved to the local repo.

* You can use `git log` to show he commit logs and `git status` to displays information about the files in the directory, e.g, whether your changed files have been staged 

* Use `git branch` to create a copy of of your current/active branch which you can work on and make changes before adding these changes to your main branch

* Use `git merge` to bring together 2 or more branches to the active main/current active branch