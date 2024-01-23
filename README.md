# credit_risk_analysis

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* This repo is hoping to create a model which will accurately predict healthy vs high risk loans based on the following attributes:
  * loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt
* Machine Learning Model 1 will attempt to predict the health of the loan based on the provided data which includes 75,036 healthy loans and 2,500 high risk loans.
* Machine Learning Model 2 will deploy a Random Over Samper tool which transforms our data to contain 56,271 healthy loans and 56,271 high risk loans.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

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
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasonin
