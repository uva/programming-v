# Software

In this course we will use the [Python programming language](http://python.org/). You'll also need an editor and/or development environment for writing and debugging your programs. In Programming in Python, we will be using IDLE, a programming environment specially designed for Python programming and included with the Python distribution. These programs are available for installation on your personal computers (see below).

## Why Python?

A programming language is the tool we use to construct a sequence of instructions that will tell the computer what we want it to do. There are hundreds of programming languages in the world. Over the course of my career, I've taught programming classes using at least at least six different languages.

There is no best language (though I could nominate some candidates for worst). Different languages are better or worse for different kinds of applications. MATLAB, for example, is a great language for manipulating vectors and matrices. C is a good language for writing the programs that control data networks.

In this course, we will use Python. Python is a relatively recent addition to the universe of languages, and is still growing in popularity. I want to emphasize that this course is not about Python. You will certainly learn Python, and that's a good thing. What is much more important, however, is that you will learn how to write programs that solve problems, given a set of basic primitives, and ways of combining them into more complex elements, that you can then abstract into primitives. This skill can be transferred to many languages.


## Setting Up Python

You can install the software on your personal computer if your operating system is GNU/Linux, Windows (7/Vista/XP), or MacOS X. In all cases, you will need Python version 2.7.x (any 2.5.x or 2.6.x version will also work, but 3.0 versions are NOT compatible). See the [releases page on python.org](http://www.python.org/download/releases/) for a list of the most common versions of python.

**Warning:** On the Python homepage, the latest version available for download is actually 3.0. Do not install this! This version is not backwards compatible with the code that you'll be writing in this course (for example, you have to type `print("test")` instead of `print "test"`). Instead, be sure to download a version listed above.

## Using IDLE

IDLE is the standard Python development environment. Its name is an acronym of "**I**ntegrated **D**eve**L**opment **E**nvironment". It works well on both Unix and Windows platforms.

It has a Python shell window, which gives you access to the Python interactive mode. It also has a file editor that lets you create and edit existing Python source files.

During the following discussion of IDLE's features, instead of passively reading along, you should start IDLE and try to replicate the actions.

You can type Python code directly into this shell, at the '>>>' prompt. Whenever you enter a complete code fragment, it will be executed. For instance, typing:

    >>> print "hello world"

and pressing Enter will cause the following to be displayed:

    hello world

IDLE can also be used as a calculator:

    >>> 4+4
    8

Addition, subtraction, and multiplication operators are built into the Python language. This means you can use them right away. If you want to use a square root in your calculation, you need to import the math module. Do not worry about what it means right now; we will cover this later during the course. Below is an example of square root calculation:

    >>> import math
    >>> math.sqrt(16)
    4.0

Math module allows you to do a number of useful operations:

    >>> import math
    >>> math.pow(3, 2)
    9.0
    >>> math.cos(0)
    1.0

Note that you only need to execute the import command once after you start IDLE.

### Exercises

For additional practice, try using IDLE to calculate:

1. 23.0 to the 5th power
2. Positive root of $$34*x^2+68*x-510$$.
   Recall:
   $$a*x^2 + b*x + c$$
   $$x1 = -b+(sqrt_(b*b-4*a*c))/(2*a)$$
