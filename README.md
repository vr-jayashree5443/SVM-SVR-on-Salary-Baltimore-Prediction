# SVM-SVR-on-Salary-Baltimore-Prediction

## Introduction
This project focuses on predicting the salary of employees working in Baltimore using Support Vector Machine for Regression (SVR) algorithm. The dataset contains salary information from July 1, 2013, to June 30, 2014.

## Steps

1. **Importing the libraries**: Necessary libraries such as numpy, pandas, matplotlib, seaborn, etc., are imported.
2. **Importing the dataset**: The dataset is loaded from the provided URL.
3. **Data Cleaning, Data Exploration, Data Manipulation, Data Visualization**: Various cleaning, exploration, manipulation, and visualization tasks are performed on the dataset.
4. **EDA - Exploratory Data Analysis**: Detailed exploration of the dataset to understand the relationships and distributions of variables.
5. **Splitting the Dataset**: Splitting the dataset into training and testing sets.
6. **Choosing the Model**: Support Vector Machine for Regression (SVR) is chosen as the predictive model.
7. **Training the Model**: The SVR model is trained on the training dataset.
8. **Testing the Model**: The trained model is tested on the testing dataset.
9. **Model Evaluation**: Evaluation metrics such as R-squared score, mean squared error, and mean absolute error are calculated to assess the model's performance.
10. **[OPTIONAL] Export the dataset into the .csv**: Exporting the cleaned dataset into a .csv file is an optional step.

## Problem Statement
Given the dataset, the task is to predict the salary of employees working in Baltimore.

## Dataset
The dataset is sourced from the provided URL: [Baltimore Salary Prediction Dataset](https://raw.githubusercontent.com/Lochana24/Baltimore-Salary-Prediction/main/train.csv).

## Machine Learning
After data preprocessing and exploration, the machine learning pipeline involves the following steps:
- **Train Test split**: Splitting the dataset into training and testing sets.
- **Data preprocessing**: Feature Scaling (Standardization) is applied to standardize the features.
- **Model selection**: Support Vector Machine for Regression (SVR) is chosen as the predictive model.
- **Training**: The SVR model is trained using the training dataset.
- **Testing and Prediction**: The trained model is tested and used to predict salaries.
- **Performance Evaluation**: The model's performance is evaluated using various metrics.

## Conclusion
In conclusion, based on the trained SVR model, we can predict the salaries of employees in Baltimore. Future employees joining on specified dates can use this model to estimate their salaries.
