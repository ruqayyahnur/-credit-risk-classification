# -credit-risk-classification
# Module 20 Report Template

## Overview of the Analysis

  This analysis focuses on loan risk. The dataset provided reflects historical lending activity from peer-to-peer lending services company to build a model
that can be used to identify the creditworthiness of borrowers. 
  The data provided various information on the common borrower, such as previous loan sizes, borrowers' income, number of accounts, total_det, and loan_status.
  The loan_status was focused on for this analysis in order to predict a healthy loan vs an unhealthily loan for the borrower.
  * The stages of the machine learning process are as followed:
        - Split the Data into training and testing sets
        - Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
        - Split the data into training and testing datasets by using train_test_split
        - Create a *Logistic Regression Model* with the *Original Data*
        - Evaluate the model’s performance by doing the following:
              - Generate a *confusion matrix*.
              - *Print the classification report*
              - Instantiate the *RandomOverSampler* model

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * **Accuracy Score:** *95%*
  * **Precision Score:** *100% percision for healthy loans* & *85% percision for high-risk loans*
  * **Recall Score:** *99% recall  for healthy loans* & *91% recall for high-risk loans*
  #### This particulary logistic regression model performed well.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
