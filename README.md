# -credit-risk-classification
# Module 20 Report Template

## Overview of the Analysis
* This analysis focuses on loan risk. The dataset provided reflects historical lending activity from peer-to-peer lending services. This data will be used build a model that can be used to identify the creditworthiness of borrowers.
* The data provided various information on the common borrower, such as previous loan sizes, borrowers' income, number of accounts, total_det, and loan_status.
* The *loan_status* was focused on for this analysis in order to predict a healthy loan vs an unhealthily loan for the borrower.
* The stages of the machine learning process are as followed:
    * Split the Data into training and testing sets
    * Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
    * Split the data into training and testing datasets by using train_test_split
    * Create a *Logistic Regression Model* with the *Original Data*
    * Evaluate the model’s performance by doing the following:
         * Generate a *confusion matrix*.
         * *Print the classification report*
         * Instantiate the *RandomOverSampler* model

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

### Machine Learning Model 1:
  * **Accuracy Score:** 95%
  * **Precision Score:** 100% precision for healthy loans & 85% precision for high-risk loans
  * **Recall Score:** 99% recall  for healthy loans & 91% recall for high-risk loans
  #### This particulary logistic regression model performed well.

### Machine Learning Model 2:
  * **Accuracy Score:** 99%
  * **Precision Score:** 100% precision for healthy loans & 84% precision for high-risk loans
  * **Recall Score:** 99% recall for both healthy loans & high-risk loans
  #### This particulary logistic regression model also performed very well.

## Summary

The results of the machine learning models revealed high accuracy scores in both models that are demonstrated. This shows that credit classfication within these models does fairly well in most situations. The high-risk loans precisions scores are in the 80% range, which is still good but may need more focus on it.
The machine learning models would be great business addition as the accuracy scores are often very high. Model 2 reflects an accuracy score of 99%. Precision scores for the high-risk loans as they are more important to keep track of, however, the model still predicts a fairly high level of precision of 84%.


