
**Credit card fraud detection using ML**

Done by 
1.Anitha Pandian
2.Lakshmi Samera Ravula
3.Jake Lackey

**Overview**

This project aims to develop a machine learning model for detecting fraudulent transactions. The model utilizes various features associated with each transaction to predict whether a transaction is fraudulent or not. 

**Project Description**

In this project, we analyze credit card transaction data to build a Machine Learning model that can identify potentially fradulent transactions. The project involves data preprocessing, feature engineering, model selection, training and evaluation.

**Dataset**

https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud?resource=download
Data set feature explanation:
distance_from_home - the distance from home where the transaction happened.
distance_from_last_transaction - the distance from last transaction happened.
ratio_to_median_purchase_price - Ratio of purchased price transaction to median purchase price.
repeat_retailer - Is the transaction happened from same retailer.
used_chip - Is the transaction through chip (credit card).
used_pin_number - Is the transaction happened by using PIN number.
online_order - Is the transaction an online order.
fraud - Is the transaction fraudulent.

**Exploratory Data Analysis**

The CSV file was read using Pyspark into a dataframe and pandas was used to import and understand the data, while SKlearn was used to normalize the data and matplotlib was used for visualization.

Bar charts were generated to show which transaction componenet has higher rate of fraud.

**Machine Learning Model**

Used 3 different methods - Logistic Regression, Random Forest and Standard scalar for prediction of fraudulent transactions in credit card activity.

Used python library by name gradio for hosting UI for ML models and Random Forest mothod was used in app for prediction.
