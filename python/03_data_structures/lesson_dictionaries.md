Let's pretend you're working on a project for your local Humane Association and you are writing a program to keep track of all the cats.  Each cat is unique. It has it's own name, age, breed, and adoption status. How would we store that information inside python?

### Learning Outcomes

By the end of this lesson, you will be able to:

* Create your own dictionary
* List all the keys of your dictionary
* Iterate over each key of your dictionary
* Add and remove keys and values to your dictionary

#### Introduction

It would make a lot of sense to store all of the cat's information inside of a dictionary. A dicttionary in Python is a key-value store. We can hold specific information inside of a key, and use that key to retreive that data. Let's look at an example.

~~~python
alfred_cat = {
    'name': 'Alfred',
    'age': 2,
    'breed': 'Siamese',
    'adopted': False 
}
~~~

You can see how easy it is to create a dictionary. We can retreive the information based on the keys as well.

~~~python
alfred_cat['adopted']  #=> False
alfred_cat['age']      #=> 2
~~~

#### Assignment

<div class="lesson-content__panel" markdown="1">

1. Read [chapter 5](https://automatetheboringstuff.com/2e/chapter5/) of _Automate the Boring Stuff with Python_. Be sure to try the practice projects at the end.

</div>

### Additional Resources

* Read through the methods you can use with Python data structures in the [official documentation](https://docs.python.org/3/tutorial/datastructures.html). Get used to reading this style of documentation as you'll be referencing it quite often.