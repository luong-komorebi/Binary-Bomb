# Binary Bomb

![](http://zpalexander.com/content/images/2016/05/phase-1-objdump.png)

## Introduction

### What is this?

* This is lab assignments taken from my course on Programming Systems with [Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/2e/labs.html) text book in use.  
* The purpose of this lab assignment is to familiarize yourself with machine-level programs and the tools that you can use to understand them. You will do this by defusing a Binary Bomb produced by Dr. Evil, a nefarious Canadian.
* __I take no credit on making this possible__ All credit goes to those people who have written the books. Some Solutions are my friends'

============

### But why ? 

__This is a very hard exercise with few resources on Google or `whatever-web-search-tool` out there, but it is awesome.__

It is so hard at first that I almost cry solving this. However, by solving this you will sharpen your skill in understanding machine code (*Assembly code*).  

> At the end of the series you would've seen how several aspects of a C program are represented in machine code, for example: local variables, registers, conditionals, loops, switch statements, arrays, recursion, structs, etc.    

__Also, this is not where you find solutions to your homework if you are taking an equivalent course at your College, or happen to come accross here by Google search. This is where I provide you with numerous bombs to challenge you. This is not made to compromise the value of the exercise for both instructors and students using CS:APP.__

=============

## Instruction

#### Read the pdf
Read the bomblab-instructions.pdf file. Skip step 1.  

#### And my explanation
You will see more than 30 folders with identical numbers (1551xxx). *Don't panic*. These numbers are my classmates' student IDs. **Each of the folder contains a unique bomb**. Although the solving technique is the same for all bombs, this was done to make sure no one can copy others' solutions. **It is therefore very good for you to pratice**.  

In each of the folder, we have 3 files :  

1. bomb.c  `this is the bomb in C code`  
2. bomb    `an executable file for you to run and debug from`  	
3. solution.txt `me and my friend's solution to defuse the bomb`    

You will need to take a look at the `bomb.c` .That file tells you that how they are making the bomb. Nevertheless, they hid the necessary source code for you to defuse the bomb, but leave you only the name of the phase that you need to by pass ( from phase_1 to phase\_6 ).  
What you need to do is : **debug the code through the executable file bomb** using a debugger (**gdb**, or **IDA**).  It is crucial that you know how to use a debugger and understand **Assembly Code**.  

Helpful Link for gdb : 	[here](http://www.yolinux.com/TUTORIALS/GDB-Commands.html). Pay close attention on : how to run a executable file, how to debug it, how to set breakpoints, how to disassemble, how to view register and their value...


That's all. Happy defusing. 

