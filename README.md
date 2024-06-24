# Titanic Survival Predictor

In this project, I've worked with the [Titanic Data Set from Kaggle](https://www.kaggle.com/c/titanic). This is a very famous data set and is often a student's first step in machine learning!

## Project Description

The objective of this project is to predict whether a passenger on the Titanic survived or not using a logistic regression model.

## Dataset

I've used a "semi-cleaned" version of the Titanic dataset. If you use the dataset hosted directly on Kaggle, you may need to do some additional cleaning not shown in this lecture notebook.

## Features of the Dataset

- **PassengerId**: Unique ID for each passenger.
- **Survived**: Survival (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Installation

To run this project, you'll need to install the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Methodology

1. Importing libraries
2. Exploratory Data Analysis
3. Finding out the missing data attributes
4. Cleaning the data
5. Converting Categorical features
6. Building a Logistic regression Model
7. And finally evaluating the results
