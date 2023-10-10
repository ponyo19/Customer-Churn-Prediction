# Customer-Churn-Prediction

## Introduction
For a business with various services, in this case, a fictional Telco company, it is essential to keep old customers because studies suggest that depending on the industry you are in, acquiring a new customer can cost five to seven times more than retaining an old one. Therefore, I created this machine learning model to predict customer churn, which promises to help businesses make better customer retention programs.

## Data
The data points of the problem represent the statistics of 7073 customers of  a fictional Telco company. The concerned label is whether the customer is going to cancel the service or not (1 for yes, 0 for no). The features include services that each customer has signed up for, customer account information, and demographic info about customers. 

The dataset was collected from Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
A newer version of the dataset is also available from IBM: https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

## Methodology
I performed feature engineering, feature selection and built two models for comparision using Logistic Regression and Decision Tree Classifier.

## Results
The final model using Logistic Regression reaches an accuracy of approximately 79% on the test set. It is compared with another model using Decision Tree Classifier, which only yields an accuracy of 73%.

## Requirements
To run this project, the following libraries should be installed:
<ul>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>Sklearn</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ul>
Note: the project was written on Python 3.11.5

