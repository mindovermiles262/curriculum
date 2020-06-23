Functions are an essential part of programming. They are an easy way to execute a task. Instead of having to write your flow control each time you want to use it, you can turn it into a function and call it much easier.

### Learning Outcomes:

By the end of this lesson, you will:

* Be able to write a function
* Understand how to use variables
* Know the difference between local and global variables

### Introduction

Now that you understand how to control the flow of your programs, we can make our lives easier by using Functions. Functions are simple ways to execute a task. Let's say you have a program where you want to make coffee. What are the steps needed for one cup of coffee? Fill the kettle, turn on the kettle, wait for the water to boil, weigh the coffee beans, grind the beans, pour water over the beans, drink. That's a lot of steps for one cup of coffee! Wouldn't it be easier to be able to call just one step to make coffee? That's what functions allow you to do. They group similar bits of code into a process. Instead of having to call all the steps above to make coffee, you could combine them all into one `make_coffee()` function.

You write functions in python by using a special `def` keyword and a colon. Function names can be almost anything you want them to be, but they should be descriptive of what the function does. Let's take a look at an example make coffee function:

~~~python
def make_coffee():
    print('Fill the kettle')
    print('Turn on the kettle')
    print('Weigh the beans')
    print('Grind the beans')
    print('Wait for the water to boil')
    print('Pour the water over the ground beans')
    print('Enjoy your coffee')
		
make_coffee() #=> Your first cup of coffee
~~~

Line 1 is the __function definition__. We want to define a function named "say_hello". All function definitions end with a colon.

Line 2 is the start of the function. You'll notice that it's indented by 4 spaces. This is how python knows what is part of the function and what's not included. We tell the function to simply print out 'Hello' to the console.

We call this newly created function on line 9. The parenthesis at the end of the name tell python that this is a function and it should be executed. If you follow along in your terminal, when you run this program you'll see the all the steps printed to your console.

Now, if you want to make a second cup of coffee, it's as easy as calling the `make_coffee()` function again.

#### Assignment

<div class="lesson-content__panel" markdown="1">

* Read [chapter 3](https://automatetheboringstuff.com/2e/chapter3/) of _Automate the Boring Stuff with Python_.

</div>

### Knowledge Check

* Functions are miniprograms within a program.
* Functions start with the `def` keyword and end with a colon. You can add arugments inside the parenthesis.
* Variables can be in either local or global scopes. You cannot use local variables in the global scope, but you CAN use global variables in a local scope.

### Exercises

* Go through Learn Python's [Function Module](https://www.learnpython.org/en/Functions). Complete the exercises at the end.

### Additional Resources

* Add any additional resources here
