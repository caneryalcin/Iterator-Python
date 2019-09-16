# Iterator-Python

This project aims to show how to use iterators in pyton.

---

# What is iterator?

Iterators are an object that can be stroll on and only return one element.
Every object that we can create iterator are iterable object.
Iterator has a protocol which consists of two methods.

## Iterators' advantages:
    -Cleaner code
    -Iterators can work with infinite sequences
    -Iterators save resources

The for statement calls the __ __iter__() __ function from container object.

The function returns an iterator object that defines the method __next__(),
which accesses elements in the container one at a time. 

The next() method returns the next element of a sequence. 
