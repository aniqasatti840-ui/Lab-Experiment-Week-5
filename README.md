# OOP Lab Manual

## Week 05

### Experiment 01

Design a Payroll class that has data members for an employee’s hourly pay rate, number of hours worked, and total pay for the week.

Write a program with an array of seven Payroll objects. The program should ask the user for the number of hours each employee has worked and will then display the amount of gross pay each has earned.

**Input Validation:**

Do not accept values greater than 60 for the number of hours worked.

---

### Experiment 02

The objective of this exercise is to understand the declaration of a class with its data members and member functions, and the concept of passing objects as function parameters.

Create a class Travel with two data members:

- kilometer
- hour

Class member functions:

```cpp
input() : void
show() : void
add(Travel p) : void
```

The `add(Travel p)` function accepts an object of Travel as a parameter, adds the values of data members of the parameter object and the calling object, and displays the result.

#### Instructions

1. Declare two objects `t1` and `t2` of class Travel and input data in both objects.
2. Call the add function with `t1` object and pass `t2` object as an argument.

---

### Experiment 03

The objective of this exercise is to understand the concept of static data members.

Write a class Capital with one static data member `count`, which counts the number of objects created of a particular class.

---

## Learning Objectives

After completing these experiments, students will be able to:

- Understand the Payroll class and object arrays.
- Apply input validation in C++ programs.
- Pass objects as function parameters.
- Perform operations using multiple objects.
- Understand and implement static data members.
- Count object instances using static variables.

## Technologies Used

- C++
- Classes and Objects
- Object Arrays
- Static Data Members
- Function Parameters
- Object-Oriented Programming
