# Linux Fundamentals

## Overview

This TryHackMe lab introduced the fundamentals of Linux and provided hands-on practice with the command line. The exercises focused on identifying the current user, displaying text, navigating directories, listing files, and reading file contents.

## Skills Demonstrated

* Linux fundamentals
* Linux command-line interface
* Directory navigation
* File listing and inspection
* Reading text files

## Commands Used

| Command  | Purpose                               |
| -------- | ------------------------------------- |
| `whoami` | Displays the currently logged-in user |
| `echo`   | Prints text to the terminal           |
| `ls`     | Lists files and directories           |
| `cd`     | Changes the current directory         |
| `cat`    | Displays the contents of a file       |
| `pwd`    | Shows the current working directory   |

## Lab Walkthrough

### Listing Files

I used the `ls` command to view the files and directories in the current location:



The output displayed several directories and a log file.

### Navigating Directories

I used `cd` to enter one of the directories:



After entering the directory, I used `ls` again to inspect its contents:




The directory contained a log file and a text file.

### Reading File Contents

I used `cat` to read the contents of the text file:



This demonstrated how files can be viewed directly from the Linux terminal.
## Key Takeaways

* Linux users interact with the operating system through commands.
* `pwd` helps confirm the current location in the filesystem.
* `ls` is useful for discovering files and directories.
* `cd` allows users to move through the directory structure.
* `cat` can be used to inspect text files.
* Understanding basic Linux commands is important for cybersecurity, system administration, and SOC investigations.

## Conclusion

This lab provided a practical introduction to the Linux command line. These commands are essential for navigating systems, reviewing files, and performing basic investigation tasks in cybersecurity environments.

