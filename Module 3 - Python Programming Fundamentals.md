# Module Introduction and Learning Objectives

This module discusses Python fundamentals and begins with the concepts of conditions and branching. Continue through the module and learn how to implement loops to iterate over sequences, create functions to perform a specific task, perform exception handling to catch errors, and how classes are needed to create objects.

## Learning Objectives

In this lesson you will learn about:

* Classify conditions and branching by identifying structured scenarios with outputs.
* Understand loops by using visual examples and comparing them to tuples and lists.
* Understand functions by building a function using inputs and outputs.
* Explain objects and classes by identifying data types and creating a class.

# Conditions and Branching

[Conditions and Branching](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-3-1-Conditions.ipynb)

## Practice Quiz: Python Programming Fundamentals

Question 1: What is the result of the following: ```1=2```

- A. [ ] ```True```
- B. [X] ```SyntaxError:can't assign to literal```
- C. [ ] ```False```

Question 2: What is the output of the following code segment: 

```
i=6 

i<5
```

- A. [ ] ```SyntaxError: can't assign to literal```
- B. [X] ```False```
- C. [ ] ```True```

Question 3: What is the result of the following: ```5!=5```

- A. [ ] ```True```
- B. [X] ```False```

Question 4: What is the output of the following code segment:```'a'=='A'```
- A. [ ] ```True```
- B. [X] ```False```

Question 5: In the video, if ```age=18``` what would be the result.

- A. [ ] You can enter
- B. [X] Move on

Question 6: In the video what would be the result if we set the variable age as follows: ```age= -10```

- A. [ ]

```
you can enter 
move on
```

- B. [X]

```
go see Meat Loaf 
move on
```

Question 7: hat is the result of the following: ```True or False```

- A. [ ] ```False```
- B. [X] ```True```, an ```or``` statement is only False if all the Boolean values are False.

# Loops

[Loops](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-3-2-Loops.ipynb)

## Practice Quiz: Loops

Question 1: What will be the output of the following: 

```
for x in range(0,3): 

print(x)
``` 

- A. [ ] 

```
0

1

2

3
```

- B. [X]

```
0

1

2
```

Question 2: What is the output of the following: 

```
for x in ['A','B','C']: 

print(x+'A') 
```

- A. [ ]

```
A

B

C
``` 

- B. [X]

```
AA

BA

CA
```

Question 3: What is the output of the following: 

```
for i,x in enumerate(['A','B','C']):

print(i,x) 
```

- A. [ ]

```
AA

BB

CC
```

- B. [X]

```
0 A

1 B

2 C
```

# Functions

[Functions](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-3-3-Functions%20.ipynb)

## Practice Quiz: Functions

Question 1: What does the following function return: ```len(['A','B',1])```?

- A. [ ] ```4```
- B. [ ] ```2```
- C. [X] ```3```

Question 2: What does the following function return: ```len([sum([0,0,1])])```?

- A. [ ] ```3```
- B. [ ] ```0```
- C. [X] ```1```

Question 3: What is the value of list L after the following code segment is run? 

```
L=[1,3,2]

sorted(L)
```

- A. [ ] ```L:[0,0,0]```
- B. [ ] ```L:[1,2,3]```
- C. [X] ```L:[1,3,2]```

Question 4: From the video what is the value of c after the following? 

```
c=add1(2)

c=add1(10)
```

- A. [ ] ```14```
- B. [X] ```11```
- C. [ ] ```3```

Question 5: What is the output of the following lines of code? 

```
def Print(A):

for a in A:

print(a+'1')

Print(['a','b','c'])
```

- A. [ ] 

```
a1
```

- B. [X] 

```
a1

b1

c1
```

- C. [ ]

```
a

b

c
```

# Exception Handling

[Exception Handling](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-3-1.2-ExceptionHandling.ipynb)

## Practice Quiz: Exception Handling

Question 1: Why do we use exception handlers?

- A. [ ] Terminate a program
- B. [X] Catch errors within a program
- C. [ ] Write a file
- D. [ ] Read a file

Question 2: What is the purpose of a ```try…except``` statement?

- A. [ ] Only executes if one condition is true
- B. [ ] Crash a program when errors occur
- C. [ ] Executes the code block only if a certain condition exists
- D. [X] Catch and handle exceptions when an error occurs

# Objects and Classes

[Objects and Classes](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-3-4-Classes.ipynb)

## Practice Quiz: Objects and Classes

Question 1: What is the type of the following? ```["a"]```

- A. [X] ```list```
- B. [ ] ```str```

Question 2: What does a method do to an object?

- A. [ ] Returns a new values.
- B. [X] Changes or interacts with the object.

Question 3: We create the object: ```Circle(3,'blue')```

What is the color attribute set to?

- A. [X] ```'blue'```
- B. [ ] ```2```

Question 4: What is the radius attribute after the following code block is run? 

```
RedCircle=Circle(10,'red') 

RedCircle.radius=1
```

- A. [ ] ```'red'```
- B. [X] ```1```
- C. [ ] ```10```

Question 5: What is the radius attribute after the following code block is run?

```
BlueCircle=Circle(10,'blue') 

BlueCircle.add_radius(20) 
```

- A. [X] ```30```
- B. [ ] ```20```
- C. [ ] ```10```

## Graded Quiz: Python Programming Fundamentals

Question 1: What value of ```x``` will produce the output? 

```
Hello

Mike
```

<img width="386" alt="Question1" src="https://user-images.githubusercontent.com/17474099/115565169-71fd3080-a2b9-11eb-89c3-39d459cf1513.png">

- A. [ ] ```x=A```
- B. [X] ```x="A"```
- C. [ ] ```x=1```

Question 2

<img width="220" alt="Question_2" src="https://user-images.githubusercontent.com/17474099/115565605-cd2f2300-a2b9-11eb-9f92-2b351a6a4652.png">

- A. [ ]

```
11

22

33
```

- B. [X]

```
2

4

6
```
