# Module Introduction and Learning Objectives

This module teaches the basics of Python and begins by exploring some of the different data types such as integers, real numbers, and strings. Continue with the module and learn how to use expressions in mathematical operations, store values in variables, and the many different ways to manipulate strings.

## Learning objectives

In this lesson, you will learn the basics of Python and you will write your first Python program:

* Demonstrate an understanding of types in python by converting/casting data types: strings, floats, integers.
* Interpret variables and solve expressions by applying mathematical operations.

# Types:

[Your First Program, Types, Expressions, and Variables](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-1-1-Write_your_first_python_code.ipynb)

## Practice Quiz: Types

Question 1: What is the type of the following: ```0```
- A. [X] Int
- B. [ ] float

Question 2: What is the type of the following number: ```3.12323```
- A. [ ] Int
- B. [X] Float

Question 3: What is the result of the following: ```int(3.99)```
- A. [ ] ```3.99```
- B. [X] ```3```

# Expressions and Variables:

[Your First Program, Types, Expressions, and Variables](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-1-1-Write_your_first_python_code.ipynb)

## Practice Quiz: Expressions and Variables

Question 1: What is the result of the following operation: ```11//2```
- A. [X] ```5```
- B. [ ] ```5.5```

Question 2: What is the value of x after the following is run:

```
x=4
x=x/2
```

- A. [ ] ```4.0```
- B. [X] ```2.0```

# String Operations:

In Python, a string is a sequence of characters.
A string is contained within two quotes.
You could also use single quotes.
A string can be spaces or digits.
A string can also be special characters.
We can bind or assign a string to another variable.
It is helpful to think of a string as an ordered sequence.
Each element in the sequence can be accessed using
an index represented by the array of numbers.
The first index can be accessed as follows:
We can access index six.
Moreover, we can access the 13th index.
We can also use negative indexing with strings.
The last element is given by the index negative one.
The first element can be obtained by index negative 15 and so on.
We can bind a string to another variable.
It is helpful to think of string as a list or tuple.
We can treat the string as a sequence and perform sequence operations.
We can also input a stride value as follows:
The two indicates we'd select every second variable.
We can also incorporate slicing.
In this case, we return every second value up to index four.
We can use the len command to obtain the length of the string.
As there are 15 elements, the result is 15.
We can concatenate or combine strings.
We use the addition symbols.
The result is a new string that is a combination of both.
We can replicate values of a string.
We simply multiply the string by the number of times we would like to replicate it-
in this case, three.
The result is a new string.
The new string consists of three copies of the original string.
This means you cannot change the value of the string, but you can create a new string.
For example, you can create a new string by setting it to
the original variable and concatenate it with a new string.
The result is a new string that changes from
Michael Jackson to Michael Jackson is the best.
Strings are immutable.
Back slashes represent the beginning of escape sequences.
Escape sequences represent strings that may be difficult to input.
For example, backslashes "n" represent a new line.
The output is given by a new line after the backslashes "n" is encountered.
Similarly, backslash "t" represents a tab.
The output is given by a tab where the backslash, "t" is.
If you want to place a backslash in your string,
use a double backslash.
The result is a backslash after the escape sequence.
We can also place an "r" in front of the string.
Now, let's take a look at string methods.
Strings are sequences and as such,
have apply methods that work on lists and tuples.
Strings also have a second set of methods that just work on strings.
When we apply a method to the string A,
we get a new string B that is different from A.
Let's do some examples.
Let's try with the method "Upper".
This method converts lowercase characters to uppercase characters.
In this example, we set the variable A to the following value.
We apply the method "Upper", and set it equal to B.
The value for B is similar to A, but all the characters are uppercase.
The method replaces a segment of the string- i.e.
a substring with a new string.
We input the part of the string we would like to change.
The second argument is what we would like to exchange the segment with.
The result is a new string with a segment changed.
The method find, find substrings.
The argument is the substring you would like to find.
The output is the first index of the sequence.
We can find the substring Jack.
If the substring is not in the string,
the output is negative one.
Check the labs for more examples.

## Practice Quiz: String Operations

Question 1: What is the result of the following: ```Name[0]```

![String_Operations_Practice_Quiz_Q1](https://user-images.githubusercontent.com/17474099/114864202-fe5aaf80-9df0-11eb-9fdb-c46a627bd889.png)

- A. [ ] ```"i"```
- B. [X] ```"M"```
- C. [ ] ```"n"```

Question 2: What is the result of the following: ```Name[-1]```

- A. [ ] ```"o"```
- B. [ ] ```"M"```
- C. [X] ```"n"```


Question 3: What is the output of the following: ```print("AB\nC\nDE")```

- A. [ ] 

```
AB

CD

E
```

- B. [ ] 

```
ABC

DE
```

- C. [X]

```
AB

C

DE
```

Question 4: What is the result of following? ```"hello Mike".find("Mike")```

If you are unsure, copy and paste the code into Jupyter Notebook and check.

- A. [ ] ```5```
- B. [X] ```6```
- C. [ ] ```6,7,8```

## Graded Quiz: Python Basics

Question 1: What is the type of the following: ```1```

- A. [X] int
- B. [ ] float
- C. [ ] str

Question 2: What is the result of the following code segment: ```1//2```?

- A. [X] ```0```
- B. [ ] ```0.5```

Question 3: In Python, if you executed ```name = 'Lizz'``` , what would be the output of ```print(name[0:2])``` ?

- A. [X] ```Li```
- B. [ ] ```L```
- C. [ ] ```Lizz```

Question 4: Consider the string ```Name="Michael Jackson"``` , what is the result of the following operation ```Name.find('el')``` ?

- A. [ ] ```-1```
- B. [ ] ```1```
- C. [X] ```5```

Question 5: What is the result of the following: ```"123".replace("12", "ab")``` ?
- A. [X] ```'ab3'```
- B. [ ] ```'123ab'```
