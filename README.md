# credit-risk-classification

Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
    NOTE
   A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.
3. Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
 - Generate a confusion matrix.
 - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report

Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.\
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

## An overview of the analysis:
* Explain the purpose of the analysis.

- The purpose of this analysis is to use supervised machine learning skills to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from lending services. 

* Explain what financial information the data was on, and what you needed to predict.
 - The data was provided in the form of a csv, which was into a Pandas dataframe. The categories in the dataframe include the following:
    - Loan Size
    - Interest Rate
    - Borrower Income
    - Debt to Income Ratio
    - Number of Accounts
    - Derogatory Marks
    - Total Debt

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

* ## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

- Accuracy Score: The accuracy score was .99 (99%), which means that the model performed with almost perfect accuracy.
- Precision Score: The precision score for the healthy loans (0) was 1.00 (100%), while the precision score for high-risk loans (1) was 0.85 (85%). This means that the healthy loans had the most reliable precision. 
- Recall Score: The recall score the healthy loans (0) was 0.99 (99%), while the recall score for the  high-risk loans (1) was 0.91 (91%). This means that the healthy loans had the most reliable 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


