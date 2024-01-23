# credit_risk_analysis

## Overview of the Analysis

* This repo is aims to create a model which will accurately predict healthy vs high risk loans based on the following attributes:
  * loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt
* Machine Learning Model 1 will attempt to predict the health of the loan based on the provided data which includes 75,036 healthy loans and 2,500 high risk loans.
* Machine Learning Model 2 will deploy a Random Over Samper tool which transforms our data to contain 56,271 healthy loans and 56,271 high risk loans.

## Results

* Machine Learning Model 1:
  * Accuracy: 99%
    * Healthy Loan: 100%
    * High Risk Loan: 88%  
  * Precision: 99%
    * Healthy Loan: 100%
    * High Risk Loan: 85%
  * Recall: 99%
    * Healthy Loan: 99%
    * High Risk Loan: 91%

* Machine Learning Model 2:
  * Accuracy: 99%
    * Healthy Loan: 100%
    * High Risk Loan: 91%
  * Precision: 99%
    * Healthy Loan: 100%
    * High Risk Loan: 84% 
  * Recall: 99%
    * Healthy Loan: 99%
    * High Risk Loan: 99% 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Machine Learning Model 1:
 * Although this model was able to accurately predict healthy loans with almost 100% accuracy, it fell short when trying to match high risk loans. Out of the total of 619 high risk loans that were tested in the model, it incorrectly labeled 56 of them as healthy. this is a ~9% recall which would be too high in this situation.
* Machine Learning Model 2:
 * Although this model does not perfectly predict healthy and risky loans, it does have a far better recall score than Model 1. only incorrectly predicting a risky loan as healthy ~1% of the time. This is the most important factor and is why I would recommend using this Model as a first line of defense. Although I think this Model can be used as a first line I think further work must be done to feel more confident in the models. (Neural Network?)

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasonin
