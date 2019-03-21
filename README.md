# Titanic: Machine Learning from Disaster Project

This is a python script used to solve the Titanic disaster project provided from https://www.kaggle.com/c/titanic

## Required Packages
- numpy
- pandas
- seaborn
- scipy
- sklearn

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

|Id   |SalePrice          |
|-----|-------------------|
|1461 |115230.71681995243 |
|1462 |153120.93123664297 |
|1463 |153120.93123664297 |
|1464 |153120.93123664297 |
|1465 |153120.93123664297 |
|1466 |153120.93123664297 |
|1467 |179566.05608812527 |
|1468 |160857.51704125153 |
|1469 |196507.14119826752 |
|1470 |119106.9144361396  |
|1471 |189141.67956958793 |
|1472 |97279.81891960099  |
|1473 |94360.46986528934  |
|1474 |143764.91615695073 |
|1475 |109120.15497533568 |
|1476 |352984.0614650302  |
|1477 |246213.34437531425 |
|1478 |301600.4487908311  |
|1479 |305541.21533308405 |

## Reference
This project is based on Kaggle notebook created by Manav Sehgal, Titanic Data Science Solutions. 
URL: https://www.kaggle.com/startupsci/titanic-data-science-solutions
