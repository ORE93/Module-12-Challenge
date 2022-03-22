# Module 12 Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    - This anaylsis was to determine which of the banks loans are healthy and which would default (unhealthy).
  
* Explain what financial information the data was on, and what you needed to predict.
    - The financial data provided was on various loans from the bank, it included data such as loan size, interest rate, borrower income and so on.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    - The value counts function showed me the loan status of the over 70000 loans.
  
* Describe the stages of the machine learning process you went through as part of this analysis.
    - First I began by importing all the necessary modules, specifically sklearns train_test_split, LogisticRegression and RandomOverSampler modules.
    - I then split the data using train_test_split.
    - After that I create my LogisticRegression model using the train data, I then fit the data using the fit function and make a prediction using the predict function.
    - I can now see my accuracy score, confusion matrix and classification report using their respective functions.
    - I then imported the RandomOverSampler and went through the same steps but this time using the oversampled data.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    - Model 1 had a 95% accuracy score along with a 100% Precision score for healthy loans and an 85% precision score for unhealthy loans.
    - It had a 99% recall score for healthy loans and a 91% recall score for unhealthy loans.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
      - Model 2 had an even better 99% accuracy score as well as 100% and 84% for healthy and unhealthy loans respectively. 
      - It had an also better 99% recall score for healthy and unhealthy loans alike.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  - The oversampled model (model 2) performed best. I know this because of it's higher accuracy score (99%) as well as its higher recall score (also 99%).
  
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    - I would say so yes. It is difficult to predict which loans will be unhealthy in this model seeing as there are so many healthy loans. 


