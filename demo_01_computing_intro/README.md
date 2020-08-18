# Introduction to Computing





## What is a computer?

At a basic level, a computer is a list of information stored in memory combined with some operations that can be performed on the information in memory. 


## What is a program? 

A computer program is a list of instructions for operations to be performed on the values stored in memory. 


## How do computers run programs? 

The human-readable computer program that you write is interpreted, or translated into another set of instructions, by another program called the interpreter. 
This interpreter translates the program into something that will run on the operating system. 
The operating system, such as Windows, Linux or Mac OS, is another set of programs that then translate your instructions into a more primitive set of instructions that are finally executed on the computer. 

<img src="Interpreter.png" width="500"/>

Why go through all of this trouble? Well, first, the operating system uncouples your program from the particulars of the hardware on your physical computer, such as the monitor, the hard drive and the keyboard. 
Further, the interpreter separates the instructions in your program from the particular operating system on your computer. 
With this separation, you need only write the instructions in standardized syntax and the interpreter and operating system take care of the rest. 


## So how does the computer *really* run programs?

To illustrate the workings of a computer, we will consider one of the simplest forms of computers, called a *register machine*.


# The Register Machine

The register machine was introduced by a logician Hao Wang at the dawn of the computing age. 
It stores information in a list of registers, each one with a natural number. 
It can perform three operations:

* ```END``` will halt the program.
* ```INC``` will increase the number in a register by 1.
* ```DEB``` will decrease the number in a register by 1, if it is nonzero, otherwise ```BRANCH```.



Simple as they are, these operations are enough to do anything that any computer can do -- it just might take a long time.
The first command is not very interesting but it is still required to declare that the program has stopped. 
The second is fairly simple and makes a primitive change to the state of the register. 
The magic occurs with the third condition. 
Subtraction is nearly the same as addition, in reverse, except that it is undefined if the particular register 


Here are some examples that follow from the discussion in the [RodRego](http://sites.tufts.edu/rodrego/) on the website of the philosopher Dan Dennet at Tufts University. 
RodRego is a program for running programs in a language called ```RAP```, which stands for *Register Assembly Programming*. 
A version that will run in your browser is available [here](http://proto.atech.tufts.edu/RodRego/).

