# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).


The purpose of the credit risk analysis was to develop a machine learning model that could accurately predict credit risk for loans, distinguishing between healthy loans and high-risk loans.

The financial information in the data likely included details such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The goal was to predict the loan status, categorizing it as either healthy (0) or high-risk (1) based on the provided financial information.

Basic information about the variables being predicted, such as the distribution of loan statuses, could be obtained through value_counts to understand the balance between healthy and high-risk loans in the dataset.

The stages of the machine learning process in this analysis may have included data preparation, separating the data into features and labels, splitting the data into training and testing sets, importing and instantiating the LogisticRegression model from scikit-learn, fitting the model, making predictions, and evaluating the model's performance using metrics like accuracy, precision, and recall.

In addition to LogisticRegression, other algorithms such as decision trees, random forests, or support vector machines (SVM) could have been used to build and compare different models for credit risk analysis. Each algorithm may offer unique advantages and may be suitable for different types of datasets or prediction tasks.
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
Machine Learning Model 1:
Accuracy score: 0.99
Precision: Class 0: 1.00 Class 1: 0.85
Recall: Class 0: 0.99 Class 1: 0.91
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Based on the results of the machine learning models:

 Linear based model and logistic regressions performed exceptionally well with an accuracy score of 0.99, high precision values for both classes, and good recall scores for both classes.

the boosted tree models seems to perform the best based on its high accuracy, precision, and recall scores. It has effectively predicted both healthy (0) and high-risk (1) loans with high precision and recall values.

The performance of the model is crucial for the problem of credit risk analysis. In this context, it is important to predict both healthy loans (0) accurately to ensure that good loans are not mistakenly classified as high-risk, as well as high-risk loans (1) to mitigate potential financial risks. Model 1's balanced precision and recall scores for both classes indicate its effectiveness in predicting both categories accurately.

Therefore, based on the performance metrics and the importance of accurately predicting both healthy and high-risk loans, I recommend using Machine Learning Model 1 for credit risk analysis.
