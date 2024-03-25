# Credit Risk Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:
* The purpose of this analysis is to be able to be able to safely loan money to loaners
* The first step was to import our necessary dependencies.
* The second step was to load in the csv data.
* The third step is to split our data into training and testing sets and then use the logistic regression from sklearn in order to make prediction based on our training data.
* In this analysis, we used Logistic Regression,

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
              precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.95      0.91       625

    accuracy                           0.99     19384
   macro avg       0.94      0.97      0.95     19384
weighted avg       0.99      0.99      0.99     19384


* Machine Learning Model 1:
    * Accuracy is 99% meaning that the model is able to predict healthy loans.
    * The precision rate is 100% meaning that there is a low false positive rate and is able to predict the healthy loans correctly.
    * The recall for predicting healthy credit is also at 100%.

## Summary

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Linear regression model performs at a high accuracy of 99%. We got a high preciusiona nd high recall value as well. The model is able to predict 0s, healthy credit, at almost a certainty. This means based on the testing and training data, the model was able to predict the data correctly. I believe predicting 

