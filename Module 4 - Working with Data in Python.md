# Module Introduction and Learning Objectives

This module explains the basics of working with data in Python and begins the path with learning how to read and write files.

Continue the module and uncover the best Python libraries that will aid in data manipulation and mathematical operations.

## Learning Objectives

In this lesson you will learn about:

* Demonstrate an open function to create and identify a file object.
* Use pandas for library and data analysis by using commands.
* Demonstrate how to create a text file by using the open function.
* Demonstrate how to use NumPy to create multi-dimensional arrays.

# Reading Files with Open

[Reading Files with Open](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-4-1-ReadFile.ipynb)

# Writing Files with Open

[Writing Files with Open](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-4-2-WriteFile.ipynb)

## Practice Quiz: Reading & Writing Files with Open

Question 1: What are the most common modes used when opening a file?

- A. [ ] (a)ppend, (c)lose, (w)rite
- B. [ ] (s)ave, (r)ead, (w)rite
- C. [ ] (a)ppend, (r)edline, (w)rite
- D. [X] (a)ppend, (r)ead, (w)rite

Question 2: What is the data attribute that will return the title of the file?

- A. [ ] ```File1.open()```
- B. [ ] ```File1.close()```
- C. [ ] ```File1.mode```
- D. [X] ```File1.name```

Question 3: What is the command that tells Python to begin a new line?

- A. [ ] ```\q```
- B. [ ] ```\b```
- C. [ ] ```\e```
- D. [X] ```\n```

Question 4: What attribute is used to input data into a file?

- A. [ ] ```File1.close()```
- B. [ ] ```File1.read()```
- C. [ ] ```File1.open()```
- D. [X] ```File1.write()```

# Pandas with IBM Watson Studio

[Loading data, saving data and working with Pandas](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-4-3-LoadData.ipynb)

## Practice Quiz: Pandas

Question 1: What python object do you cast to a dataframe?

- A. [X] Dictionary
- B. [ ] Set

Question 2: How would you access the first-row and first column in the dataframe ```df```?

- A. [ ] ```df.ix[1,0]```
- B. [ ] ```df.ix[0,1]```
- C. [X] ```df.ix[0,0]```

Question 3: What is the proper way to load a CSV file using pandas?

- A. [ ] ```pandas.import_csv(‘data.csv’)```
- B. [ ] ```pandas.load_csv(‘data.csv’)```
- C. [X] ```pandas.read_csv(‘data.csv’)```
- D. [ ] ```pandas.from_csv(‘data.csv’)```

![PandasPracQuizQ4](https://user-images.githubusercontent.com/17474099/115770753-5ecb8d00-a3ad-11eb-82ed-5d7cdc467acb.png)

Question 4: Use this dataframe to answer the question. How would you select the Genre disco?

- A. [ ] ```df.loc[‘Bee Gees’, ‘Genre’]```
- B. [ ] ```df.loc[6, 5]```
- C. [X] ```df.iloc[6, 4]```
- D. [ ] ```df.iloc[6, ‘genre’]```

Question 5: Use this dataframe to answer the question. Which will NOT evaluate to ```20.6```, select all that apply?

- A. [ ] ```df.iloc[4,5]```
- B. [ ] ```df.iloc[6,5]```
- C. [X] ```df.loc[4,’Music Recording Sales’]```
- D. [X] ```df.iloc[6, ‘Music Recording Sales (millions)’]```

Question 6: Use this dataframe to answer the question. How do we select Albums The Dark Side of the Moon to Their Greatest Hits (1971-1975)? Select all that apply.

- A. [ ] ```df.iloc[2:5, ‘Album’]```
- B. [X] ```df.loc[2:5, ‘Album’]```
- C. [X] ```df.iloc[2:6, 1]```
- D. [ ] ```df.loc[2:5, 1]```

# One Dimensional NumPy

[One dimensional NumPy](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-5-1-Numpy1D.ipynb)

# Two Dimensional NumPy

[Two dimensional NumPy](https://github.com/1965Eric/IBM-PY0101EN-Python-Basics-for-Data-Science/blob/main/PY0101EN-5-2-Numpy2D.ipynb)

## Practice Quiz: Numpy in Python

Question 1: What is the Python library used for scientific computing and is a basis for Pandas?

- A. [ ] datetime
- B. [ ] Requests
- C. [ ] Tkinter
- D. [X] Numpy

Question 2: What attribute is used to retrieve the number of elements in an array?

- A. [ ] ```a.dtype```
- B. [ ] ```a.ndim```
- C. [ ] ```a.shape```
- D. [X] ```a.size```

Question 3: How would you change the first element to "10" in this array? ```c:array([100,1,2,3,0])```

- A. [ ] ```c[4]=10```
- B. [ ] ```c[2]=10```
- C. [ ] ```c[1]=10```
- D. [X] ```c[0]=10```

Question 4: What attribute is used to return the number of dimensions in an array?

- A. [ ] ```a.dtype```
- B. [ ] ```a.size```
- C. [ ] ```a.shape```
- D. [X] ```a.ndim```

## Graded Quiz: Working with Data in Python

Question 1: Consider the following text file: ```Example1.txt```: 

```
This is line 1 

This is line 2 

This is line 3
```

What is the output of the following lines of code?

<img width="611" alt="mod4q1" src="https://user-images.githubusercontent.com/17474099/116419186-185ab000-a83d-11eb-81b6-e4200c57c8cc.png">

- A. [ ]

```
This is line 1 

This is line 2 

This is line 3
```

- B. [X]

```This is line 1```

- C. [ ]

```
This is line 1 

This is line 2
```

Question 2: Consider the file object: ```File1```. How would you read the first line of text?

- A. [ ]

```
File1.readline ()

File1.readline ()
```
 
- B. [X]

```File1.readline ()```

- C. [ ]

```
File1.read ()
```

Question 3: What is the result of applying the following method ```df.head()```, to the dataframe ```df``` ?

- A. [ ] prints the first column of the dataframe
- B. [X] prints the first 5 rows of the dataframe
- C. [ ] prints the first 100 rows of the dataframe

Question 4: Consider the dataframe ```df```. How would you access the element in the 1st row 3rd column? ?

- A. [ ] ```df.iloc[2,0]```
- B. [X] ```df.iloc[0,2]```
- C. [ ] ```df.iloc[1,3]```

Question 5: What is the result of the following lines of code?

<img width="349" alt="mod4q5" src="https://user-images.githubusercontent.com/17474099/116420559-5d331680-a83e-11eb-89e9-46171bf7a5a9.png">

- A. [ ] ```0```
- B. [X] ```array([0, 0, 0, 0, 0])]```
- C. [ ] ```array([1, 1, 1, 1, 1])```

