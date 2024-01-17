# Customer-churn-prediction

Abstract 
Customer churn prediction for a telecom company. Customers who left within the last month is called Churn. For each customer, there is information about how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, total charges, and others. Given that information, this project aims to answer if it is possibile to predict whether a customer will stop doing business with the company. To answer it, an artificial neural network was utilized with 80% accuracy on the respective test data. So yes, it is possible to predict customer churn from the given data.

Data and Methods
Data: This project uses data from Telco Customer Churn downloaded from https://www.kaggle.com/datasets/blastchar/telco-customer-churn. The data set includes information about: Customers who left within the last month – the column is called Churn Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges Demographic info about customers – gender, age range, and if they have partners and dependents

Methods: 
Correlation matrix, heatmap, univariate selection, deep learning (tensorflow), histogram, confusion matrix, stratified hold out split

Results: 
An artificial neural network was utilized with 80% accuracy on the respective test data. So yes, it is possible to predict customer churn from the given data.

# House price prediction

This is a regression analysis project. The goal is to predict a house price based on a number of inputs such as total area, number of rooms, location and others.
This project is intended for educational purposes only.
The dataset is download from Kaggle for the city in India - Bengaluru.

The data was downloaded from kaggle: https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data

# Ecommerce text classification

The aim of this project is to categorize text descriptions into 4 distinct categories. The dataset required for this project can be accessed at https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification?select=ecommerceDataset.csv. Multiple text classification algorithms are employed in this project to demonstrate their varying levels of accuracy.
- Bag of words with SVM
- Bag of words and Lemmatization with SVM
- N-grams with SVM
- TF-IDF with SVM

TF-IDF produces best results with 98% accuracy. Bag of words yields 96%. N-grams does not improve previous result, but takes much longer to train.