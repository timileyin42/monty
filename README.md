# monty interpreter in C

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project was to create an interpreter for Monty ByteCodes files in C language.

# synopsis

## Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument and the file can contain blank lines (empty or made of spaces only, and any additional text after the opcode or its required argument is not taken into account:

Example:
File monty_test.m

push 0 Push 0 onto the stack$
push 1 Push 1 onto the stack$

push 2
  push 3
                   pall



push 4

    push 5
      push    6

pall This is the end of our program. Monty is awesome!$

# Getting Started
These instructions will get you a copy of the project up and running on your local machine (Linux distro) for development and testing purposes.

# Installing
You will need to clone the repository of the project from Github. This will contain the Monty Interpreter program and all of its dependencies.

https://github.com/Timileyin42/monty.git

After cloning the repository you will have a folder called monty. In here there will be several files that allow the program to work.
