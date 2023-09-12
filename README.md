# credit-risk-classification

In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending 
services company to build a model that can identify the creditworthiness of borrowers.

Split the Data into Training and Testing Sets:

I opened the starter code notebook and used it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Created the labels set (y) from the “loan_status” column, and then created the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.


Create a Logistic Regression Model with the Original Data:

I used my knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluated the model’s performance by doing the following:

Generated a confusion matrix.

Printed the classification report.

Answered the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

