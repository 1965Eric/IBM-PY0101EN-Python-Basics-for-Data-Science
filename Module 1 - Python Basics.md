# Types:

A type is how Python represents different types of data.
In this video, we will discuss some widely used types in Python.
You can have different types in Python.
They can be integers like 11, real numbers like 21.213, they can even be words.
Integers, real numbers, and words can be expressed as different data types.
The following chart summarizes three data types for the last examples.
The first column indicates the expression.
The second column indicates the data type.
We can see the actual data type in Python by using the type command.
We can have int, which stands for an integer and float that stands for
float, essentially a real number.
The type string is a sequence of characters.
Here are some integers.
Integers can be negative or positive.
It should be noted that there is a finite range of integers but it is quite large.
Floats are real numbers.
They include the integers but also numbers in between the integers.
Consider the numbers between 0 and 1.
We can select numbers in between them.
These numbers are floats.
Similarly, consider the numbers between 0.5 and 0.6.
We can select numbers in between them.
These are floats as well.
We can continue the process zooming in for different numbers.
Of course there is a limit but it is quite small.
You can change the type of the expression in Python, this is called typecasting.
You can convert an int to a float.
For example, you can convert or cast the integer 2 to a float 2.0.
Nothing really changes, if you cast a float to an integer, you must be careful.
For example, if you cast the float 1.1 to 1, you will lose some information.
If a string contains an integer value, you can convert it to int.
If we convert a string that contains a non-integer value, we get an error.
Check out more examples in the lab.
You can convert an int to a string or a float to a string.
Boolean is another important type in Python.
A Boolean can take on two values.
The first value is True, just remember we use an uppercase T.
Boolean values can also be False with an uppercase F.
Using the type command on a Boolean value, we obtain the term bool.
This is short for Boolean, if we cast a Boolean True to an integer or
float, we will get a 1.
If we cast a Boolean False to an integer or float, we get a 0.
If you cast a 1 to a Boolean, you get a True.
Similarly, if you cast a 0 to a Boolean, you get a False.
Check the labs for more examples or
check Python.org for other kinds of types in Python.

## Practice Quiz: Types

Question 1: What is the type of the following: 0
- A. [X] Int
- B. [ ] float

Question 2: What is the type of the following number: 3.12323
- A. [ ] Int
- B. [X] Float

Question 3: What is the result of the following: int(3.99)
- A. [ ] 3.99
- B. [X] 3

# Expressions and Variables:

In this video, we will cover expressions and variables.
Expressions describe a type of operation the computers perform.
Expressions are operations the python performs. For example,
basic arithmetic operations like adding multiple numbers.
The result in this case is 160.
We call the numbers operands, and the math symbols in this case,
addition, are called operators.
We can perform operations such as traction using the subtraction sign.
In this case, the result is a negative number.
We can perform multiplication operations using the asterisk. The result is 25.
In this case, the operands are given by negative and asterisk.
We can also perform division with the forward slash-
25 / 5 is 5.0;
25 / 6 is approximately 4.167.
In Python 3, the version we will be using in this course, both will result in a float.
We can use the double slash for integer division, where the result is rounded.
Be aware, in some cases the results are not the same as regular division.
Python follows mathematical conventions when performing mathematical expressions.
The following operations are in a different order.
In both cases, Python performs multiplication,
then addition, to obtain the final result.
There are a lot more operations you can do with Python, check the labs for
more examples.
We will also be covering more complex operations throughout he course.
The expressions in the parentheses are performed first.
We then multiply the result by 60.
The result is 1,920.
Now, let's look at variables.
We can use variables to store values. In this case, we assign a value of 1 to
the variable my_variable using the assignment operator, i.e, the equal sign.
We can then use the value somewhere else in the code
by typing the exact name of the variable.
We will use a colon to denote the value of the variable.
We can assign a new value to my_variable using the assignment operator.
We assign a value of 10. The variable now has a value of 10.
The old value of the variable is not important.
We can store the results of expressions. For example, we add several values and
assign the result to x. X now stores the result.
We can also perform operations on x and save the result to a new variable-y.
Y now has a value of 2.666.
We can also perform operations on x and assign the value x.
The variable x now has a value: 2.666.
As before, the old value of x is not important.
We can use the type command in variables as well.
It's good practice to use meaningful variable names; so,
you don't have to keep track of what the variable is doing.
Let say, we would like to convert the number of minutes
in the highlighted examples to number of hours in the following music data-set.
We call the variable, that contains the total number of minutes, total_min.
It's common to use the underscore to represent the start of a new word.
You could also use a capital letter.
We call the variable that contains the total number of hours, total_hour.
We can obtain the total number of hours by dividing total_min by 60.
The result is approximately 2.367 hours.
If we modify the value of the first variable,
the value of the variable will change.
The final result values change accordingly, but
we do not have to modify the rest of the code.

## Practice Quiz: Expressions and Variables

Question 1: What is the result of the following operation: 11//2
- A. [X] 5
- B. [ ] 5.5

Question 2: What is the value of x after the following is run:

```
x=4
x=x/2
```

- A. [ ] 4.0
- B. [X] 2.0
