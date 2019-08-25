# A study on Titanic Passenger Survival Prediction using Logistic Regression.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
The sinking of the Titanic on April 15th, 1912 is one of the most tragic tragedies in history. The Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers. The numbers of survivors were low due to the lack of lifeboats for all passengers and crew. Some passengers were more likely to survive than others, such as women, children, and upper-class. This case study analyzes what sorts of people were likely to survive this tragedy. 

`Predictors:`
```
Pclass: Ticket class
Sex: Sex
Age: Age in years
Sibsp: Number of siblings / spouses aboard
Parch: Number of parents / children aboard
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton
```

`Target:`
```
Survived: Survival (0 = No, 1 = Yes)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_Logistic_Regression_Titanic_Survival/blob/master/Train_Titanic.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Logistic_Regression_Titanic_Survival/blob/master/Logistic%20Regression%20-%20Titanic%20Survival.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Exploring the Descriptive Statistics of the Variables
      3.2 Exploring the Variables
      3.3 Data Cleaning
      3.4 Data Scaling
      3.5 Handing Catagorized Variables
    4 Train Test Split
    5 Select and Train a Model
      5.1 Linear Regression Model
    6 Apply Model on Test Set
    ```
    
### Model Performance
The model has an average `Precision` & `Recall` of 82%.
![alt text](https://github.com/zhenyu92/ML_Logistic_Regression_Titanic_Survival/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
