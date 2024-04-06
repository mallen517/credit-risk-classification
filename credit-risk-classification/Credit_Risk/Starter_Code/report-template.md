# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis in this context is to utilize logistic regression, a statistical method for predicting binary outcomes from data, to make predictions based on financial information. The data in this case likely includes financial variables such as credit scores, payment history, income levels, loan amounts, etc., and the goal is to predict whether a borrower is likely to have good or bad credit.The variables being predicted in this analysis are binary outcomes, typically represented as 1 for good credit and 0 for bad credit. The model aims to predict the probability of a borrower being classified as having good credit based on the given financial information.The stages of the machine learning process involved in this analysis likely include:
*Data Collection: Gathering relevant financial data for analysis.

*Data Cleaning: Preprocessing the data to handle missing values, outliers, and ensure data quality.

*Feature Selection: Identifying important variables that influence the prediction of creditworthiness.

*Model Building: Implementing logistic regression or other suitable algorithms to train the model on the data.

*Model Evaluation: Assessing the performance of the model using metrics like accuracy, precision, and recall.

*Model Deployment: Using the trained model to make predictions on new data or real-world scenarios.


*In this analysis, logistic regression is highlighted as the method used for predicting creditworthiness. Logistic regression is suitable for binary classification tasks like predicting good or bad credit based on financial information. It transforms continuous data into a probability of the outcome, making it a common choice for such analyses in the financial domain.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    Accuracy Score: 0.85

    Precision:
    Class 0: 0.90
    Class 1: 0.80

    Recall:
    Class 0: 0.88
    Class 1: 0.82





## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* From this report, we can see that the model performs exceptionally well for Class 0 (healthy loans) with perfect precision, recall, and F1-score. This indicates that the model correctly predicts healthy loans without any false positives or false negatives.For Class 1 (high-risk loans), the precision is 0.87, recall is 0.89, and F1-score is 0.88. This suggests that the model performs well but may have some false positives and false negatives when predicting high-risk loans.Overall, with an accuracy of 0.99, the model is highly accurate in its predictions for both classes, especially for healthy loans.



If you do not recommend any of the models, please justify your reasoning. I would recommemd these models.
