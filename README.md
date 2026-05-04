# Walmart Sales Prediction using Linear Regression
## Project Overview

This project focuses on predicting weekly sales using a real-world Walmart dataset sourced from Kaggle. The goal is to understand how machine learning can be applied to business data and to implement an end-to-end workflow from data preprocessing to model evaluation.

## 🎯 Objectives
Analyze and understand the dataset
Prepare and clean the data for modeling
Apply Linear Regression to predict weekly sales
Evaluate model performance using appropriate metrics
Visualize results for better interpretation

## 🛠️ Workflow
Data Loading
Imported dataset using Pandas
### Data Preprocessing
Cleaned column names
Converted date column into datetime format
Handled formatting issues
### Feature Engineering
Converted date into numerical (ordinal) format
Separated features (X) and target variable (y)
### Train-Test Split
Split dataset into 80% training and 20% testing
### Model Building
Implemented Linear Regression using Scikit-learn
### Model Evaluation
Used Mean Squared Error (MSE)
Used R² Score for performance analysis
### Visualization
Compared training vs testing R² scores using bar plots

## 📈 Key Insights
Data preprocessing plays a crucial role in model performance
Feature engineering (especially date conversion) is essential
Linear Regression works well for basic relationships but may not capture complex patterns
Comparing training and testing performance helps detect overfitting

## 🧰 Technologies Used
Python
Pandas
Scikit-learn
Matplotlib
Seaborn

## 🚀 Future Improvements
Apply advanced models like Random Forest or XGBoost
Perform deeper feature engineering
Hyperparameter tuning for better accuracy
