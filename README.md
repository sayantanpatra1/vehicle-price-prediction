# Vehicle Price Prediction (Regression Problem)
This project aims to predict vehicle prices based on various features such as mileage, engine type, number of doors, and dimensions using regression models. The implementation includes data preprocessing, feature engineering, and model evaluation to achieve accurate price predictions.
# Table of Contents
Dataset
Features
Steps Involved
Models Used
Performance Metrics
Results
Conclusion
Requirements
Usage
# Dataset
The dataset used in this project is loaded from auto.txt, containing various attributes of vehicles required for predicting prices.

# Features
- mileage: Vehicle mileage
- engine type: Type of engine
- number of doors: Number of doors in the vehicle
- length, width, height: Dimensions of the vehicle
- engine capacity: Engine capacity in cc
- And other relevant features
# Steps Involved
1. Load the Data: Load the dataset into a pandas DataFrame.
2. Clean the Data: Replace missing values and correct data types.
3. Feature Engineering: Convert categorical data to numerical values.
4. Handle Missing Values: Fill NaN values with appropriate statistics.
5. Split Data: Split the data into training and testing sets.
6. Train Models: Train multiple regression models on the training set.
7. Evaluate Models: Evaluate the performance of the models on the testing set.
# Models Used
- Linear Regression
- Lasso Regression
- Ridge Regression
# Performance Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
# Results
- The project implements and compares three regression models.
- The performance of each model is evaluated based on RMSE.
- Visualizations of predicted vs actual prices are provided.
# Conclusion
Linear Regression showed a certain error margin.
Lasso and Ridge regressions were also tested for comparison.
The project highlights the importance of feature selection and data preprocessing in improving model performance.
