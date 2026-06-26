# Credit-Card-Fraud-Detection
Credit Card Fraud Detection using Machine Learning
📌 Project Overview

This project builds a machine learning model to detect fraudulent credit card transactions. Since fraud cases are extremely rare compared to legitimate transactions, the dataset is highly imbalanced. To address this challenge, the project applies data preprocessing, feature scaling, and SMOTE (Synthetic Minority Oversampling Technique) to balance the classes before training multiple classification models.

The objective is to accurately classify fraudulent transactions while minimizing false positives and false negatives.

🚀 Features
Data loading and preprocessing
Duplicate record removal
Feature scaling using StandardScaler
Exploratory Data Analysis (EDA)
Handling imbalanced data with SMOTE
Train-test split
Training multiple machine learning models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Model comparison and evaluation
📂 Dataset

The project uses the Credit Card Fraud Detection dataset.

Dataset Features

Numerical features: V1 to V28
Amount – Transaction amount
Class
0 → Legitimate Transaction
1 → Fraudulent Transaction

Note: The Time column is removed during preprocessing because it does not significantly contribute to prediction.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)
📊 Workflow
Load the dataset
Check dataset information and missing values
Remove duplicate records
Drop unnecessary columns (Time)
Normalize the Amount column using StandardScaler
Perform Exploratory Data Analysis
Handle class imbalance using SMOTE
Split the dataset into training and testing sets
Train multiple machine learning models
Compare model performance and select the best model
🤖 Machine Learning Models
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
📈 Results

The models are trained on the balanced dataset generated using SMOTE. Their performance can be evaluated using metrics such as:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix

Random Forest generally performs well for fraud detection because it effectively captures complex patterns in the data.
