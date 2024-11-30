# Bengaluru House Price Prediction using Linear Regression

This repository contains a machine learning project focused on predicting house prices in Bengaluru using Linear Regression. The project involves various data preprocessing and feature engineering techniques to improve the accuracy of the model.

## Project Overview

The goal of this project is to build a predictive model that estimates house prices in Bengaluru based on several features such as location, size, and other attributes. The model uses **Linear Regression** to predict the target variable (house price).

## Steps Taken

### 1. **Data Cleaning**
   - Cleaned missing values in the dataset to ensure no null or missing data remains.
   
### 2. **Feature Engineering**
   - Created new features to improve the performance of the model based on domain knowledge and data exploration.

### 3. **Dimensionality Reduction**
   - Applied dimensionality reduction techniques to reduce the complexity of the data and improve model performance.

### 4. **Outlier Removal**
   - Outliers were removed using business logic and data analysis, ensuring that the data is cleaner and more suitable for modeling.

### 5. **Scatter Plot for Outlier Detection**
   - Used scatter plots to visually identify and remove outliers that might negatively impact the model's accuracy.

### 6. **One-Hot Encoding**
   - Applied **One-Hot Encoding** on the "location" column to convert categorical data into numerical format for model compatibility.

### 7. **Model Building (Linear Regression)**
   - Used **Linear Regression** to build a predictive model for house price prediction.
   
### 8. **Model Evaluation**
   - Evaluated the model’s performance using metrics such as **R-squared**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.

## Requirements

- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computing.
- **matplotlib**: Plotting graphs.

