# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to predict credit card risk using different machine learning methods and decide which of them performed the best.

## Results
* Random Oversampling had an accuracy score of 63%, a precision score of 1%, and a recall score of 59%.

![Oversampling Results](https://github.com/bflem/Credit_Risk_Analysis/blob/main/17result_pics/oversample%20result.PNG)

* SMOTE had an accuracy score of 65%, a precision score of 1%, and a recall score of 67%.
* Undersampling had an accuracy score of 53%, a precision score of 1%, and a recall score of 61%.
* SMOTEENN had an accuracy score of 64%, a precision score of 1%, and a recall score of 70%.
* Balanced Random Forest Classifier had an accuracy score of 80%, a precision score of 4%, and a recall score of 68%.
* AdaBoost Classifier had an accuracy score of 93%, a precision score of 7%, and a recall score of 91%.

![AdaBoost Results](https://github.com/bflem/Credit_Risk_Analysis/blob/main/17result_pics/adaboost%20result.PNG)

## Summary
Most of the models had a poor precision score with accuracy and recall scores in the 60's and 70's. It is clear that the ensemble methods were better than the others in this scenario. It would be my recommendation to use the Adaboost Classifier due to its high accuracy score of 93% and sensitivity score of 91%. Sensitivity is more important than precision in a credit risk situation.
