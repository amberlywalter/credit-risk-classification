# credit-risk-classification
## Overview of the Analysis

The dataset of historical lending activity included 77,536 records with the following financial information: 

•    loan size 
•    interest rate
•    borrower’s income
•    debt to income ratio
•    number of accounts 
•    whether there were any derogatory marks 
•    total debt 
•    loan status (whether it was a healthy loan, or high-risk loan)

The model created would be predicting the status of the loan (‘0’ healthy or ‘1’ high-risk) based on the given financial information. The initial technique used was to split data into training set and testing set. This training set was used to create the first Logistic Regression Model. This model was created by using the LogisticRegression module from SKLearn to fit the training data. After the training set was fit, the testing set was used to make predictions.

In addition, a second model was created using a resampling method. RandomOverSampler from imbalanced-learn was used to create a second training set. In this second training set, the loan status label had an equal number of data points. There were 56,277 data points for both ‘0’ and ‘1’. This training set was fit to the Logistic Regression Model and then the testing set was used to make new predictions.
 


## Results

* Machine Learning Model 1:
•    Accuracy: 94%
•    Precision: Predicted ‘0’ with 100% accuracy and ‘1’ with 87% accuracy
•    Recall: Predicted ‘0’ with 100% and ‘1’ with 89% accuracy

* Machine Learning Model 2:
•    Accuracy: 99%
•    Precision: Predicted ‘0’ with 100% accuracy and ‘1’ with 87% accuracy
•    Recall: Predicted ‘0’ with 100% and ‘1’ with 100% accuracy

## Summary

After reviewing both models, according to the results from accuracy, precision, and recall scores, the second machine learning model seems to perform best, as it performed with a higher accuracy of 99%. I would recommend using the second model because of this higher accuracy rate. 
