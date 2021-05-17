# Learning Objectives

* Analyze Python data using a dataset
* Identify three Python libraries and describe their uses
* Read data using Python's Pandas package
* Demonstrate how to import and export data in Python

## Practice Quiz: Understanding the Data

Question 1: Each column contains a:

- A. [ ] different used car
- B. [X] attribute or feature

## Practice Quiz: Python Packages for Data Science

Question 1: What description best describes the library Pandas?

- A. [ ] Includes functions for some advanced math problems as listed in the slide as well as data visualization.
- B. [X] Offers data structure and tools for effective data manipulation and analysis. It provides fast access to structured data. The primary instrument of Pandas is a two-dimensional table consisting of columns and rows labels which are called a DataFrame. It is designed to provide an easy indexing function.
- C. [ ] Uses arrays as their inputs and outputs. It can be extended to objects for matrices, and with a little change of coding, developers perform fast array processing.

## Practice Quiz: Importing and Exporting Data in Python

Question 1: Some common encodings are ...

- A. [X] csv
- B. [X] xlsx
- C. [ ] Pandas

Question 2: What does the following method do to the dataframe? df : df.head(12)

- A. [X] Show the first 12 rows of dataframe.
- B. [ ] Shows the bottom 12 rows of dataframe.

## Practice Quiz: Getting Started Analyzing Data in Python

Question 1: To enable a summary of all the columns, what must the parameter include be set to for the method describe?

- A. [X] ```df.describe(include=“all”)```
- B. [ ] ```df.describe(include=“None”)```

## Lesson summary

In this lesson, you have learned how to:

* **Define the Business Problem**: Look at the data and make some high-level decision on what kind of analysis should be done
* **Import and Export Data in Python**: How to import data from multiple data sources using the Pandas library and how to export files into different formats.
* **Analyze Data in Python**: How to do some introductory analysis in Python using functions like ```dataframe.head()``` to view the first few lines of the dataset, ```dataframe.info()``` to view the column names and data types.

## Importing Data Sets

[Importing Data Sets](https://github.com/1965Eric/IBM-DA0101EN-Analyzing-Data-with-Python/blob/main/DA0101EN-Review-Introduction.ipynb)

## Graded Quiz: Importing Data Sets

Question 1: What do we want to predict from the dataset?

- A. [X] price
- B. [ ] colour
- C. [ ] make

Question 2: Select the libraries you will use for this course:

- A. [X] pandas
- B. [ ] matplotlib
- C. [ ] scikit-learn

Question 3: What task does the following command perform?

```df.to_csv("A.csv")```

- A. [X] Save the dataframe ```df``` to a csv file called ```"A.csv"```
- B. [ ] load the data from a csv file called "A" into a dataframe
- C. [ ] change the name of the column to ```"A.csv"```

