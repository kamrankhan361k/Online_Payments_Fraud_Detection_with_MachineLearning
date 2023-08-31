# Online_Payments_Fraud_Detection_with_MachineLearning

The introduction of online payment systems has helped a lot in the ease of payments. But, at the same time, it increased in payment frauds. Online payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting online payment fraud is very important for credit card companies to ensure that the customers are not getting charged for the products and services they never paid. If you want to learn how to detect online payment frauds, this article is for you. In this article, I will take you through the task of online payments fraud detection with machine learning using Python.

Online Payments Fraud Detection with Machine Learning
To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud. For this task, I collected a dataset from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:

1 step: represents a unit of time where 1 step equals 1 hour
2 type: type of online transaction
3 amount: the amount of the transaction
4 nameOrig: customer starting the transaction
5 oldbalanceOrg: balance before the transaction
6 newbalanceOrig: balance after the transaction
7 nameDest: recipient of the transaction
8 oldbalanceDest: initial balance of recipient before the transaction
9 newbalanceDest: the new balance of recipient after the transaction
10 isFraud: fraud transaction
I hope you now know about the data I am using for the online payment fraud detection task. Now in the section below, I’ll explain how we can use machine learning to detect online payment fraud using Python.
