In this lesson we're going to assume that you have no prior knowledge of programming. We're going to walk you through the basics of programming and write your first python program. It may not be all that exciting of a program, but we'll build on them in the future. We've got a lot to cover so let's get started.

### Learning Outcomes

By the end of this section, you should be able to do the following:

* Execute a Python script from the command line
* Know how to use flow control
* Understand Boolean Operators

### Introduction

### Writing Your First Program
Let's not waste any time. Let's write our first python program. The main objective of this is to show you how to run python scripts from your terminal.

First, we'll make a new directory to save our script file. Open up your terminal and change directories to your home:

~~~bash
cd ~
~~~

Then, we'll create a new folder named "odin", and another folder named "python" inside of it. Then we'll `cd` into it:

~~~bash
mkdir -p odin/python
cd odin/python
~~~
Next, create a new file and name it `hello_world.py`. Then open the file inside of your code editor (VSCode)

~~~bash
touch hello_world.py
code hello_world.py
~~~

If you've followed along correctly you should now see an open Visual Studio Code application. Type the following and save the file:

~~~python
# This program prints 'hello world' to the terminal
print('Hello World')
~~~


### Running Your First Program
Back in your terminal (still inside the python directory), simply type the following to execute your first program:

~~~bash
python3 hello_world.py
~~~

You should see the flowing output:

~~~bash
$ python3 hello_world.py
Hello World
~~~

The dollar sign in this example is simply an indicator that you'll enter the command in your terminal as a non-root user. You shouldn't type the `$` character into your terminal.

The first command, `python3`, tells the OS to run the python 3 program. The second argument, `hello_world.py`, tells python 3 to run your script. While running the loaded script, python is instructed to print the words 'Hello World' to the terminal.

Congratulations! You've just run your first Python program!

### Assignment

<div class="lesson-content__panel" markdown="1">

1. Read [Chapter 0](https://automatetheboringstuff.com/2e/chapter0/) of _Automate The Boring Stuff with Python_ up to the "About This Book" section
1. Read [Chapter 1](https://automatetheboringstuff.com/2e/chapter1/) of _Automate the Boring Stuff with Python_ and learn the basics of using the Python interactive shell. __PRO TIP:__ Launch Python's interactive shell by typing `python` into your terminal. Type `exit()` to exit.
1. Switch it up! Code along with Al Sweigart (Author of the book you're reading) in [this youtube video](https://youtu.be/buMTH6ICnqk?t=10) of the same lesson you just read. Use the method described above in [Running your first program](#) to run the python scripts you write. Practice makes perfect
* TODO: Link "Running your first program" to paragraph above

</div>

### Knowledge Check
* Programming is a great way to perform repetitive tasks
* You do not need to be a math genius. Basic algebra is enough.
* Type `python` into your terminal to launch the interactive shell.
* There are three types of data: Integers, Floats, and Strings.

### Exercises
* Do the practice questions at the end of [Chapter 1](https://automatetheboringstuff.com/2e/chapter1/) 
* Complete the exercises at the end of learnpython.org's [Hello World](https://www.learnpython.org/en/Hello%2C_World%21) and [Variable and Types](https://www.learnpython.org/en/Variables_and_Types)

### Additional Resources
* Solidify what you learned in Chapter 1 by watching [Lesson 2](https://youtu.be/7qHMXu99d88?t=70) on Youtube. Use Python's built in interactive shell to follow along.
