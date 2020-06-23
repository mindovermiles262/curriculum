Data structures are ways of storing various sets of variables. In Python there are two main data structures, Lists and Dictionaries. Let's first talk about a List and it's closely-related cousin, the Tuple.

### Learning Outcomes:

By the end of this lesson, you will:

* Know what a list is
* Know what a tuple is
* Know how to create both lists and tuples
* Know how to add or change data in a list
* Be able to create your own Magic 8-Ball


### Introduction

Lists are a simple way to store a collection of variables. Say, for example, we want to record the temperature outside each hour. A good way to store this data is in a *list*.  A list is nothing more than a flat collection of variabiles. Let's take a look:

~~~python
temps = []  # Create an empty list
temps.append(78)
temps.append(81)
temps.append(88)
temps.append(91)
temps.append(90)
temps.append(87)
temps.append(80)

print(temps)  #=> [78, 81, 88, 91, 90, 87, 80]
~~~

Lists are also very versitile. They can store any type of variable, or any mixture of variables. Both the following are correct:

~~~python
first_list = [12.5, 2.6]
second_list = [True, 12, "String"]
~~~

Tuples are closely related to lists. The only difference is tuples are non-mutatabe; You cannot change the values once they are set.

#### Assignment

<div class="lesson-content__panel" markdown="1">

* Read [chapter 4](https://automatetheboringstuff.com/2e/chapter4/) of _Automate the Boring Stuff with Python_.

</div>

### Knowledge Check

* A list is a value that contains multiple values in an ordered sequence.
* A tuple is a list which is ordered and unchangeable.
* Use Python's `len()` function to determine the size of a list
* You can iterate over a list with a `for` loop
* `in` and `not in` can tell you if a value is in the specified list
* Add additional information to the end of a list using the `append()` method
* Use the `insert()` method to add data to the list at a spcific location

### Exercises

* Complete questions 1-5 of [W3 School's Python List Exercise](https://www.w3resource.com/python-exercises/list/)

### Additional Resources

* Add any additional resources here
