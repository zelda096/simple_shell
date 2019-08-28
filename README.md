# Simple_Shell
---
A Unix shell is a command-line interpreter

## Estructure
this project is focused on creating a shell from 0 that provides a command line user interface for unix operating systems.

### How to use ?
this shell prototype is similar to the one that comes by default in our linux operating system.

Here is our list of functions you can use with our shell:

|       Files        |                               Descriptions                                  |
|--------------------|-----------------------------------------------------------------------------|
|    shell.c         | Contains all the prototypes of each function we use in the project.         |
|    builting.c      | Are the functions that compile the commands that are requested in the shell.|
|    helper.c        | In them are the functions that get the logitude of a string, releases       |
|                    | pointers and returns errors if the command line is empty.                   |
|    parcing.c       | Analyzes command line looking for arguments converts character into tokens. |
|    pahtFinder.c    | The functions of this file acts as an interface that finds an index         |
|                    |  in the environmental variable and separates the string into directories.   |
|                    |  and paths so that they can be parsed and executed by the program.          |
|    printnumber.c   | Function that prints a number.                                              |
|    string.c        | functions that buy strings are copied and printed by a string               |

with these files the compiler is generated and we execute it with ./name and it will show us the shell to be worked receiving arguments.


### How to install?

to make the installation of this shell we will make:
```
* Clone the repository
* go to the "clone or download" button.
* Copy the url from the repository.
* Open the command terminal.
* Use the command "git clone" followed by the url.
```
additionally you give enter later to copy the repository in your command terminal and there they will have this shell.

