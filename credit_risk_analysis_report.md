# Credit Risk Analysis Report

## Overview of the Analysis

The objective of this analysis is to develop a machine learning model using supervised learning techniques, which can predict whether a loan is considered high-risk or healthy.

Two different logistic regression models were used as part of the loan risk analysis, the first model was, using the original dataset to train, fit, and predict the risk  using LogisticRegression. The second model used oversampling of the data using RandomOverSampler to balance the data.

Finally, the performance of each model was evaluated based on the balance accuracy score, the confusion matrix, the precision score, recall score, and f1-score in the classification report.

## Results


* Machine Learning Model 1: When trained on the initial dataset, Model 1 demonstrated a high level of accuracy in predicting healthy loans, achieving both precision and recall scores of 1.00 and 0.99, respectively. However, the model's ability to predict high-risk loans could benefit from improvement. The precision score of 0.85 indicates that the model correctly identified only 85% of all high-risk loans, while the recall score of 0.91 indicates that the model missed identifying 9% of all high-risk loans present in the dataset.
  



* Machine Learning Model 2: After being trained on the resampled data, Model 2 was found to be entirely accurate in predicting healthy loan labels, achieving both a precision and a recall score of 1.00 and 0.99, respectively. Additionally, the model performed well in identifying healthy loans. While the precision score for high-risk loans remained at 0.84, indicating that only 84% of actual high-risk loans were correctly classified, the recall score improved to 0.99, signifying that the model was able to now identify all high-risk loans present in the dataset.
  

## Summary

The analysis suggests that Model 2 is superior to Model 1 when it comes to predicting high-risk loans, and it exhibits a higher accuracy in predicting both labels overall. More specifically, Model 2's precision in identifying high-risk loans is relatively high, and it successfully classified all high-risk loans in the dataset. These results indicate a favorable performance within this context. 

The dataset contains a disproportionately small number of high-risk loans compared to healthy loans, which limits the potential for the model to learn from these loans. If additional high-risk loans were included in the dataset, it is possible that the performance of the model could be improved.

Therefore, based on the results, it is recommended to use Model 2 to identify high-risk loans and to achieve an overall better label-predicting accuracy.