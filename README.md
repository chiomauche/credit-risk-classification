# credit-risk-classification

* I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending 
services company to build a model that can identify the creditworthiness of borrowers.

# step 1
* Split the Data into Training and Testing Sets by using train_test_split

![Alt text](<Screenshot 2023-10-21 070005.png>)


* I created a Logistic Regression Model with the Original Data

![Alt text](<Screenshot 2023-10-21 070227.png>)


* I saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

![Alt text](<Screenshot 2023-10-21 070659.png>)

# STEP 2
* I evaluated the model’s performance by generating a confusion matrix

![Alt text](<Screenshot 2023-10-21 071002.png>)

* Printed the classification report.

![Alt text](<Screenshot 2023-10-21 071059.png>)

* Answered the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Answer: The model is very good at predicting 0 (healthy loan), as the f1-score is 1.00. However, the model have high scores in both 0 and 1 labels.It appears that the model is unable to accurately predict high-risk loans (1) to some extent, as a significant portion (around 10%) of the loans categorized as high-risk were classified as healthy. This may be attributed to a scarcity of labeled data on high-risk loans, which limits the model's ability to learn and generalize accurately.

* I created a Logistic Regression Model with Resampled Training Data

![Alt text](<Screenshot 2023-10-24 021713.png>)

