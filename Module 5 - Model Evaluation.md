# Learning Objectives

* Describe data model refinement techniques
* Explain overfitting, underfitting, and model selection
* Apply ridge regression to regularize and reduce the standard errors to avoid overfitting a regression model
* Apply grid search techniques to Python data

## Practice Quiz: Model Evaluation

Question 1: What function randomly splits a dataset into training and testing subsets

- A. [ ] ```cross_val_predict```
- B. [ ] ```cross_val_score```
- C. [X] ```train_test_split```

## Practice Quiz: Overfitting, Underfitting and Model Selection

Question 1: In the following plot, the vertical axis shows the mean square error and the horizontal axis represents the order of the polynomial. The red line represents the training error the blue line is the test error. Should you select the 16 order polynomial.

![3-8](https://user-images.githubusercontent.com/17474099/119517776-33570c00-bd78-11eb-9c8f-84a2c0838063.png)

- A. [X] No
- B. [ ] Yes

## Reading: Ridge Regression Introduction

Ridge regression is a regression that is employed in a Multiple regression model when Multicollinearity occurs. Multicollinearity is when there is a strong relationship among the independent variables. Ridge regression is very common with polynomial regression. Ridge regression is used to regularize and reduce the standard errors to avoid over-fitting a regression model.

## Practice Quiz: Ridge Regression

Question 1: The following models were all trained on the same data. Select the model with the lowest value for alpha:

![3-10](https://user-images.githubusercontent.com/17474099/119526378-a0ba6b00-bd7f-11eb-83a6-2a0e7f271552.png)

- A. [X] a
- B. [ ] b
- C. [ ] c

