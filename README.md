# Home Credit Default Risk Analysis
 
## Introduction
The objective of this project is to use historical loan application data to predict whether or not an applicant will be able to repay a loan. In this project, we will explore several models including Classification Models and Regression Models to predict the TARGET variable and Grid Search with combination of Pipeline for hyperparameter tuning.

## Data Source
Data source: https://www.kaggle.com/c/home-credit-default-risk

Since the raw dataset is too complex, we only use a part of the whole dataset - the application_train data(the main data with information about each loan application at Home Credit.) And every loan has its own row and is identified by the feature SK_ID_CURR(which is useless and we will drop it later).
The data comes with the TARGET indicating 0: the loan was repaid or 1: the loan was not repaid.

## Results
![image](https://github.com/danleiQ/Home-Credit-Default-Risk-Analysis/blob/main/Results.png)
