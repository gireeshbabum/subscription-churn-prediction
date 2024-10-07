# Subscription Churn Prediction Capstone Project

Author: Gireesh Melath

## Executive Summary
This project aims to build a predictive model that identifies the likelihood of a customer canceling their subscription, also known as churn. Using machine learning techniques, this project analyzes various customer-related features to determine which factors are most significant in predicting churn.

## Rationale
In today’s subscription-based businesses, retaining customers is critical for sustained revenue growth. Predicting churn early allows companies to take proactive measures, such as targeted marketing or improved customer service, to retain their customers. This project aims to provide actionable insights into customer behavior and identify strategies to reduce churn.

## Research Question
What factors influence subscription churn, and how accurately can we predict whether a customer will churn based on historical data?

## Data Sources
The dataset used in this project contains 24 features, including customer subscription data, app usage metrics, device information, and payment history. The target field is the *PAYING_FLAG*, which indicates whether the customer is a paying subscriber or not.


## Methodology
1. Exploratory Data Analysis (EDA): We first explore the dataset by visualizing distributions and relationships between features.
2. Data Preprocessing: Handling categorical variables, filling missing values, and scaling numerical data. PCA (Principal Component Analysis) is used to reduce dimensionality.
3. Modeling: Multiple machine learning models are trained and compared, including Logistic Regression, Random Forest, and XGBoost, to identify the best model for predicting churn.
4. Evaluation: We evaluate the models based on metrics such as accuracy, precision, recall, F1-score, and AUC (Area Under the Curve).
5. Feature Importance: Visualizing the most influential features contributing to churn.

## Results
The logistic regression model achieved an accuracy of 75%. However, the performance for classifying churners (class 0) was initially poor, leading to adjustments like oversampling and threshold tuning to improve class balance.

## Key Findings
1. Certain features, such as app usage frequency and payment history, were strong indicators of whether a customer would churn.
2. Imbalanced data posed challenges, but oversampling methods helped improve model performance, especially for identifying potential churners.
3. Implement the best-performing model in a real-time environment to monitor customer behavior and trigger interventions.
4. Continue collecting more data to retrain and refine the model.

## Outline of Project

https://github.com/gireeshbabum/subscription-churn-prediction.git

