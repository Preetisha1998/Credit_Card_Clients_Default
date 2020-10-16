# Credit_Card_Clients_Default
# Statement:
Our client is a credit card company. They have brought us a dataset that includes some demographics and recent financial data (the past six months) for a sample of 30,000 of their account holders. This data is at the credit account level; in other words, there is one row for each account (you should always clarify what the definition of a row is, in a dataset). Rows are labeled by whether in the next month after the six month historical data period, an account owner has defaulted, or in other words, failed to make the minimum payment.

The problem statement we are trying to address here is a classification problem. We have a dataset that has the payment history of a particular account holder, using this we need to predict whether a particular account holder will be a defaulter in the next month or not.

So, Let's evaluate our model with different Evaluation metrices as the metrices provide us how effective our model is.

## Deployed on `Heroku` using `Streamlit`. 
[The link to the app is here](https://creditcardclient.herokuapp.com/) 
Sometimes it may not work due to limited dynos in free tier on Heroku.

This App is meant to check how effective our model is for Credit Card Default Prediction with the help of evaluation metrices.

The evaluation metrices used here are - 
1. Confusion Matrix
2. ROC Curve
3. Precision Recall Curve

Also, along with Accuracy, there is a precision and recall score as per the model hyperparameters.

For Logistic Regression, The Model Hyperparameters are - 

1. C(Regularization Parameter) 
2. Max no. of iterations.

For Random Forest, The Model Hyperparameters are - 

1. No. of trees in forest
2. Depth of trees 
3. Bootstrap sample(True/False).

So, tune the Hyperparameters and choose the evaluation metrices and then click on Classify.

Also, You can go through the Raw Data by clicking on Show Raw Data.
