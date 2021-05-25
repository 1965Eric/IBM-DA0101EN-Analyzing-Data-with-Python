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

## Lesson Summary

In this lesson, you have learned how to:

* **Identify over-fitting and under-fitting in a predictive model**: Overfitting occurs when a function is too closely fit to the training data points and captures the noise of the data. Underfitting refers to a model that can't model the training data or capture the trend of the data.
* **Apply Ridge Regression to linear regression models**: Ridge regression is a regression that is employed in a Multiple regression model when Multicollinearity occurs.
* **Tune hyper-parameters of an estimator using Grid search**: Grid search is a time-efficient tuning technique that exhaustively computes the optimum values of hyperparameters performed on specific parameter values of estimators.

## Model Evaluation and Refinement

[Model Evaluation and Refinement](

## Graded Quiz: Model Refinement

Question 1: What is the code to create a ridge regression object ```RR``` with an alpha term equal to 10?

- A. [X] ```RR=Ridge(alpha=10)```
- B. [ ] ```RR=Ridge(alpha=1)```
- C. [ ] ```RR=LinearRegression(alpha=10)```

Question 2: What dictionary value would we use to perform a grid search for the following values of alpha? 1,10, 100. No other parameter values should be tested

- A. [ ] ```[{'alpha': [0.001,0.1,1, 10, 100, 1000,10000,100000,100000],'normalize':[True,False]}]```
- B. [X] ```[{'alpha': [1,10,100]}]```
- C. [ ] ```alpha=[1,10,100]```

Question 3: You have a linear model; the average ```R^2``` value on your training data is 0.5, you perform a 100th order polynomial transform on your data then use these values to train another model. After this step, your average ```R^2``` is 0.99; which of the following comments is correct?

- A. [X] The results on your training data is not the best indicator of how your model performs; you should use your test data to get a better idea
- B. [ ] You should always use the simplest model
- C. [ ] 100-th order polynomial will work better on unseen data

Question 4: Consider the following diagram of 4 fold cross-validation. From the diagram how many folds are used for training?

![3-11](https://user-images.githubusercontent.com/17474099/119534448-35749700-bd87-11eb-9d69-869eb5617718.png)

- A. [ ] 1
- B. [X] 3
- C. [ ] 4

Question 5: The following is an example of what?

![3-12](https://user-images.githubusercontent.com/17474099/119534853-aae06780-bd87-11eb-8abc-1616be7ab8fa.png)

- A. [ ] Overfitting
- B. [ ] Perfect fit
- C. [X] Underfitting
