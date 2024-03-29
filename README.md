0x16. C - Simple Shell

C

Group project

Syscall

 By: Julien Barbier

 Weight: 10

 Project to be done in teams of 2 people (your team: Mfumu Mabunda, Olaoluwa Anigboro-Napoleon)

 Project over - took place from Nov 2, 2022 6:00 AM to Nov 17, 2022 6:00 AM

 An auto review will be launched at the deadline

In a nutshell…

Contribution: 100.0%

Auto QA review: 0.0/55 mandatory & 0.0/76 optional

Altogether:  0.0%

Mandatory: 0.0%

Optional: 0.0%

Contribution: 100.0%

Calculation:  100.0% * (0.0% + (0.0% * 0.0%) )  == 0.0%

Challenge #3 has started!

Concepts

For this project, we expect you to look at these concepts:



Everything you need to know to start coding your own shell

Approaching a Project

Background Context

Write a simple UNIX command interpreter.







^ “The Gates of Shell”, by Spencer Cheng, featuring Julien Barbier



Resources

Read or watch:



Unix shell

Thompson shell

Ken Thompson

Everything you need to know to start coding your own shell concept page

man or help:



sh (Run sh as well)

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:



General

Who designed and implemented the original Unix operating system

Who wrote the first version of the UNIX shell

Who invented the B programming language (the direct predecessor to the C programming language)

Who is Ken Thompson

How does a shell work

What is a pid and a ppid

How to manipulate the environment of the current process

What is the difference between a function and a system call

How to create processes

What are the three prototypes of main

How does the shell use the PATH to find the programs

How to execute another program with the execve system call

How to suspend the execution of a process until one of its children terminates

What is EOF / “end-of-file”?

Copyright - Plagiarism

You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.

You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.

You are not allowed to publish any content of this project.

Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements

General

Allowed editors: vi, vim, emacs

All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89

All your files should end with a new line

A README.md file, at the root of the folder of the project is mandatory

Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl

Your shell should not have any memory leaks

No more than 5 functions per file

All your header files should be include guarded

Use system calls only when you need to (why?)

Write a README with the description of your project

You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. Format, see Docker

GitHub

*There should be one project repository per group. If you and your partner have a repository with the same name in both your accounts, you risk a 0% score. Add your partner as a collaborator. *



More Info

Output

Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.

The only difference is when you print an error, the name of the program must be equivalent to your argv[0] (See below)

Example of error with sh:



$ echo "qwerty" | /bin/sh

/bin/sh: 1: qwerty: not found

$ echo "qwerty" | /bin/../bin/sh

/bin/../bin/sh: 1: qwerty: not found

$

Same error with your program hsh:



$ echo "qwerty" | ./hsh

./hsh: 1: qwerty: not found

$ echo "qwerty" | ./././hsh

./././hsh: 1: qwerty: not found

$


