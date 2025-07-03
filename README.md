# Linux & Shell Scripting

## Operating System

An operating system (OS) is something that acts a bridge between software and hardware.

An OS is essential system software that manages computer hardware and software resources, acting as an intermediary between the user and the computer. 

## Why Linux ?

1. Free and Opensource
2. Secure - No need to install any anti-virues software
3. Different types of distributions are provided. Like Ubuntu, CentOS, Alpine etc...
4. Fast

### Kernel - Heart of Linux OS. 

The Linux kernel is the core component of a Linux operating system, acting as a bridge between hardware and software. 
It manages resources like memory, CPU, and input/output devices, enabling the OS to function.

## Shell Scripting

"Shell" is a way to talk to OS.

### shebang

In computing, a shebang is the character sequence #! (number sign and exclamation mark) at the beginning of a script.

The shebang line specifies the interpreter (like Bash, Python, etc.) that should be used to execute the script.

Example: #/bin/bash

#### Bash

Bash (Bourne Again SHell) is a widely used command language interpreter


### Shell Commands

  - ls : list files and folders
  - pwd : Present working directory
  - cd : Change directory
  - ls - ltr : To list files & folders with its properties
  - touch : To Create a file
  - vi : To create a file and write in to the file.
  - :wq! : To save the file
  - cat : To print the file
  - mkdir : Make/create directory
  - rm -r <directory-name> : To delete directory
  - free -g : To get memory details
  - nproc - To check no.of CPU's
  - df -h : Disk size
  - top  : To get all Memorry, CPU & Disk details in one place
  - history : To get history of commands executed
  - 

#### chmod

The chmod command in Linux-like operating systems is used to change the access permissions of files and directories

'chmod' is divided into 3 catgeroies

    1. Owner / administrator access
    2. Group user access
    3. Other users

Access can be granted to a file using numbers. 

example to give access to all users - chmod 777 <file_name>

  4 - Read
  2 - Write
  1 - execute

  sum of 4+2+1 = 7, means user can have access to read, write and execute






