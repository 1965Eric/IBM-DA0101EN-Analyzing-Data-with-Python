# Learning Objectives

* Describe how to handle missing values
* Describe data formatting techniques
* Describe data normalization
* Demonstrate the use of binning
* Demonstrate the use of categorical variables

## Practice Quiz: Dealing with Missing Values in Python

Question 1: How would you access the column ```”body-style"``` from the dataframe ```df```?

- A. [X] ```df["body-style"]```
- B. [ ] ```df=="bodystyle"```

Question 2: What is the correct symbol for missing data?

- A. [X] nan
- B. [ ] no-data

## Practice Quiz: Data Formatting in Python

Question 1: How would you rename the column ```"city_mpg"``` to ```"city-L/100km"```?

- A. [ ] ```df.rename(columns={”city_mpg”: “city-L/100km”})```
- B. [X] ```df.rename(columns={”city_mpg”: “city-L/100km”}, inplace=True)```

## Practice Quiz: Data Normalization in Python

Question 1: Which of the following is the correct formula for z -score or data standardization?

![2-1](https://user-images.githubusercontent.com/17474099/118642561-d25d9000-b7db-11eb-995f-c8f9a766f48a.png)

```c```

## Practice Quiz: Turning Categorical Variables into Quantitative Variables in Python

Question 1: Why do we convert values of Categorical Variables into numerical values?

- A. [X] Most statistical models cannot take in objects or strings as inputs
- B. [ ] To save memory

## Lesson Summary

In this lesson, you have learned how to:

* **Identify and Handle Missing Values**: Drop rows with incomplete information and impute missing data using the mean values.
* **Understand Data Formatting**: Wrangle features in a dataset and make them meaningful for data analysis.
* **Apply normalization to a data set**: By understanding the relevance of using feature scaling on your data and how normalization and standardization have varying effects on your data analysis.

## Data Wrangling



