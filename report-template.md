# Module 20 Report

## Overview of the Analysis

* The purpose of this analysis is to identify the credit-worthiness of borrowers.

* The data used was historical lending data that included loan size, interest rate, borrower income, debt to income ratio, the number of accounts, any derogatory amrks, total debt and the loan status. 

* The purpose of the model is to predict either a healthy loan status or a high risk loan status for future borrowers.

* After pulling in the dataset and creating the labels set from the features, the data was then split into training and testing datasets.The model was then instantiated and fit using the training data. Predictions were then made on the testing data so an evaluation could be performed to determine the model's accuracy. 

* LogisticRegression was used to fit the data and make predictions. Then the balanced_accuracy_score, confusion_matrix and classification_report were all used in this process.

## Results

* Machine Learning Model 1:
  * Balanced Accuracy: 94%
  * Precision:  Healthy loan: 100% -- High-risk loan: 87%
  * Recall:  Healthy loan: 100% -- High-risk loan: 89%


* Machine Learning Model 2:
  * Balanced Accuracy: 99%
  * Precision:  Healthy loan: 100% -- High-risk loan: 87%
  * Recall:  Healthy loan: 100% -- High-risk loan: 100%

## Summary

* Ultimately, Model 2 does seem to have a higher accuracy overall however I would not recommend using either model at this point and time.

* This is a great starting point but further testing with new and incomming datasets on Model 2 would be needed to continue  improving the model before it is used for it's purpose.

