# Module Introduction and Learning Objectives

This module begins a journey into Python data structures by explaining the use of lists and tuples and how they are able to store collections of data in a single variable.

Next, learn about dictionaries and how they function by storing data in pairs of keys and values, and end with Python sets to learn how this type of collection can appear in any order and will only contain unique elements.

## Learning Objectives

In this lesson you will:

* Understand tuples and lists by describing and manipulating tuple combinations and list data structures.
* Demonstrate understanding of dictionaries by writing structures with correct keys and values.
* Understand the differences between sets, tuples, and lists by creating sets.

# Lists and Tuples

[Lists](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-2-2-Lists.ipynb)

[Tuples](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-2-1-Tuples.ipynb)

## Practice Quiz: Lists and Tuples

Question 1: Consider the following tuple: ```say_what=('say',' what', 'you', 'will')```

What is the result of the following ```say_what[-1]``` ? 

- A. [X] ```'will'```
- B. [ ] ```'what'```
- C. [ ] ```'you'```
- D. [ ] ```'say'```

Question 2: Consider the following tuple ```A=(1,2,3,4,5)```, what is the result of the following: ```A[1:4]```:
- A. [ ] ```(2, 3, 4, 5)```
- B. [ ] ```(3, 4, 5)```
- C. [X] ```(2, 3, 4)```

Question 3: Consider the following tuple ```A=(1,2,3,4,5)```. What is the result of the following: ```len(A)```

- A. [ ] ```6```
- B. [X] ```5```
- C. [ ] ```4```

Question 4. Consider the following list ```B=[1,2,[3,'a'],[4,'b']]```. What is the result of the following: ```B[3][1]```

- A. [ ] ```c```
- B. [X] ```b```
- C. [ ] ```[4,"b"]```

Question 5: What is the result of the following operation? ```[1,2,3]+[1,1,1]```

- A. [ ] ```TypeError```
- B. [X] ```[1, 2, 3, 1, 1, 1]```
- C. [ ] ```[2,3,4]```


Question 6: What is the length of the list ```A = [1]``` after the following operation: ```A.append([2,3,4,5])```

- A. [X] ```2```
- B. [ ] ```5```

Question 7: What is the result of the following: ```"Hello Mike".split()```
- A. [ ] ```["H"]```
- B. [ ] ```["HelloMike"]```
- C. [X] ```["Hello","Mike"]```

# Dictionaries

[Dictionaries](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-2-4-Dictionaries.ipynb)

## Practice Quiz: Dictionaries

Question 1: What are the keys of the following dictionary: ```{"a":1,"b":2}```

- A. [ ] ```1,2```
- B. [X] ```"a","b"```

Question 2: Consider the following Python Dictionary: ```Dict={"A":1,"B":"2","C":[3,3,3],"D":(4,4,4),'E':5,'F':6}``` What is the result of the following operation: ```Dict["D"]```

- A. [ ] ```[3,3,3]```
- B. [X] ```(4, 4, 4)```
- C. [ ] ```1```

# Sets

[Sets](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-2-3-Sets.ipynb)

## Practice Quiz: Sets

Question 1: Consider the following set: ```{"A","A"}```. What will the result be when the set is created?
- A. [X] ```{"A"}```
- B. [ ] ```{"A","A"}```

Question 2: What is the result of the following: ```type(set([1,2,3]))```

- A. [ ] list
- B. [X] set

Question 3: What method do you use to add an element to a set?

- A. [X] ```add```
- B. [ ] ```extend```
- C. [ ] ```append```

Question 4: What is the result of the following operation: ```{'a','b'} & {'a'}```
- A. [ ] ```{'a','b'}```
- B. [X] ```{'a}```

## Graded Quiz: Python Data Structures

Question 1: Consider the tuple ```tuple1=("A","B","C" )```, what is the result of the following operation ```tuple1[-1]```?
- A. [ ] ```"A"```
- B. [X] ```"C"```
- C. [ ] ```"B"```

Question 2: Consider the tuple ```A=((1),[2,3],[4])```, that contains a tuple and list. What is the result of the following operation ```A[2]```?
- A. [ ] ```[2,3]```
- B. [X] ```[4]```
- C. [ ] ```1```

Question 3: Consider the following dictionary: ```{ "The Bodyguard":"1992", "Saturday Night Fever":"1977" }```

Select the values

- A. [X] ```"1977"```
- B. [X] ```"1992"```
- C. [ ] ```"The Bodyguard"```
- D. [ ] ```"Saturday Night Fever"```

Question 4: The variable ```release_year_dict``` is a Python Dictionary, what is the result of applying the following method: ```release_year_dict.keys()```?

- A. [X] retrieve the keys of the dictionary
- B. [ ] retrieves, the values of the dictionary

Question 5: What is the result of the following: ```'1' in {'1','2'}```?
- A. [X] True
- B. [ ] False
