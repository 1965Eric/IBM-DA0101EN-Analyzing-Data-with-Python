# Learning Objective

* Create a Jupyter notebook.
* Apply data analysis and modeling techniques to housing price data

## Reading: Project Case Scenario

In this assignment, you are a Data Analyst working at a Real Estate Investment Trust. The Trust will like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. A template notebook is provided in the lab; your job is to complete the ten questions. Some hints to the questions are given in the template notebook.

You will use Watson Studio to perform the analysis, and share an image of your finished Jupyter notebook with a URL. If you are not familiar with how to set up Watson Studio, the next section will work you through creating an instance in Watson Studio otherwise, use the following information to get the final Notebook and get started:

Notebook URL: Create a Notebook in Watson Studio and use the option ‘From URL’ to import the final notebook. Copy the link given below: https://cocl.us/da0101en_coursera_labb

## Peer-Graded Assignment: Final Assignment

[Instructions Final Assignment](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/instructions.md.html)

[Dataset](https://www.kaggle.com/harlfoxem/housesalesprediction?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-coursesedxorg-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDA0101ENSkillsNetwork20235326-2021-01-01)

[IBM Watson Setup](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/IBM_Watson_Setup.md.html)

[Upload your Notebook](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/UploadnotebookDA.md.html)

[Answers Final Assignment](https://eu-gb.dataplatform.cloud.ibm.com/analytics/notebooks/v2/f3f7dc1b-b6da-48c1-90c2-084864ddf4ab/view?access_token=ee472eb47701b434cd7b2c1c85993444517c2dd02a100db4fc36b28de1ce7e60)

## Final Exam

Question 1: What is the acronym for comma separated values?

- A. [ ] ```csepv```
- B. [ ] ```cosv```
- C. [X] ```csv```

Question 2: What Python library is used forstatistical modelling including regression and classification?

- A. [ ] Matplotlib
- B. [X] Scikit-learn
- C. [ ] Numpy

Question 3: What tells us the way the data is encoded?

- A. [X] Encoding scheme
- B. [ ] File path
- C. [ ] Data path

Question 4: What does the ```tail()``` method return?

- A. [ ] It returns the data types of each column
- B. [X] It returns the last five rows
- C. [ ] It returns the first five rows

Question 5: In a dataset what is the name of the columns?

- A. [ ] Type
- B. [X] Header
- C. [ ] Row

Question 6: The Scikit-learning library is mostly used for what?

- A. [X] Machine learning
- B. [ ] Data visualization
- C. [ ] Data analysis

Question 7: What would the following code segment output from a dataframe df?

```df.tail(10)``` 

- A. [ ] It would return all of the rows of the dataframe
- B. [X] It would return the last 10 rows of the dataframe
- C. [ ] It would return the first 10 rows of the dataframe
 
Question 8: What does the following code segment perform in a dataframe? 

```mean = df["normalized-losses"].mean() df["normalized-losses"].replace(np.nan, mean)```

- A. [ ] It drops all of the rows in the column "normalized-losses"
- B. [X] It replaces the missing values in the column "normalized-losses" with the mean of that column
- C. [ ] It drops rows that contain missing values

Question 9: How would you multiply each element in the column ```df["c"]``` by 5 and assign it back to the column ```df["c"]```?

- A. [ ] ```df["a"]=df["c"]*5```
- B. [X] ```df["c"]=5*df["c"]```
- C. [ ] ```5*df["b"]```

Question 10: What does the below code segment give an example of for the column “length”?

```df["length"] = (df["length"]-df["length"].mean())/df["length"].std()```

- A. [ ] It gives an example of the max-min method
- B. [X] It gives an example of the z-score or standard score

