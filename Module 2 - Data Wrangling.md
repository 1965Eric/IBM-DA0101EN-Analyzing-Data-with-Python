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

[Data Wrangling](https://github.com/1965Eric/IBM-DA0101EN-Analyzing-Data-with-Python/blob/main/DA0101EN-Data-wrangling.ipynb)

## Graded Quiz: Data Wrangling

Question 1: What task do the following lines of code perform?

```
avg=df['horsepower'].mean(axis=0)

df['horsepower'].replace(np.nan, avg)
```

- A. [ ] calculate the mean value for the ```'horsepower'``` column and replace all the NaN values of that column by the mean value
- B. [X] nothing; because the parameter ```inplace``` is not set to true
- C. [ ] replace all the ```NaN``` values with the mean.

Question 2: Consider the dataframe ```df```; convert the column ```df["city-mpg"]``` to ```df["city-L/100km']``` by dividing 235 by each element in the column ```'city-mpg'```.

- A. [ ] ```df['city-L/100km'] = df["city-mpg"].diV(235)```
- B. [X] ```df['city-L/100km'] = 235/df["city-mpg"]```

Question 3: What data type is the following set of numbers? ```666, 1.1,232,23.12```

- A. [X] float
- B. [ ] int
- C. [ ] object

Question 4: The following code is an example of:

```
(df["length"]-df["length"].mean())/df["length"].std()
```

- A. [ ] simple feature scaling
- B. [X] z-score
- C. [ ] min-max scaling

Question 5: Consider the two columns ```'horsepower'```, and ```'horsepower-binned'```; from the dataframe ```df```; how many categories are there in the ```'horsepower-binned'``` column?

