# Titanic: Machine Learning from Disaster Project

This is a python script used to solve the Titanic disaster project provided from https://www.kaggle.com/c/titanic

## Required Packages
- numpy
- pandas
- seaborn
- scipy
- sklearn

## How to run it
```
You can use either Jupyter Notebook or Colab. 
We used raw data url path in GitHub, so you do not need to download train.csv or test.csv. 
If you are using Jupyter Notebook, note that when exporting data to csv files, remember to change the path. 
If you are using Colab, you can uncomment the code at the end, and download csv files. 
```

## File Explanation
- train.train.csv ：raw training data set
- test.csv ：raw test data set
- Project2.ipynb ：main program
- submissiondt.csv ：decision tree result
- submissionlg.csv ：logistic regression result
- submissionper.csv ：perceptron result
- submissionrf.csv ：random forest result

## Important Variables Explanation
- train : raw training set.
- test : raw test set.
- Survived : Survived .
- full : new data set combined with training set and test set.
- final: new data set combined with training set and test set and selected features removed.
- x_train : training set after preprocessing.
- y_train : actual result of training set.
- x_test : test set after preprocessing.
- dt_pred : prediction result calculated by decision tree model.
- lg_pred : prediction result calculated by logistic regression model.
- per_pred : prediction result calculated by perceptron  model.
- rf_pred : prediction result calculated by random forest model.


## Partial Results Display

|PassengerId   |Survived    |
|--------------|------------|
|892           |0           |
|893           |0           |
|894           |0           |
|895           |0           |
|896           |1           |
|897           |0           |
|898           |1           |
|899           |0           |
|900           |0           |
|901           |0           |
|902           |0           |
|903           |0           |
|904           |1           |
|905           |0           |
|906           |1           |
|907           |1           |
|908           |0           |
|909           |0           |
|910           |1           |


## Current Kaggle Public Leaderboard Rank

|#    |Team Name    |Score    |
|-----|-------------|---------|
| 825 | Joy Gao.    | 0.80861 |

Score was calculated by Categorization Accuracy.

## Reference
This project is based on Kaggle notebook created by Manav Sehgal, Titanic Data Science Solutions. 

URL: https://www.kaggle.com/startupsci/titanic-data-science-solutions

train.csv, test.csv are available on Kaggle. 

URL: https://www.kaggle.com/c/titanic/data
