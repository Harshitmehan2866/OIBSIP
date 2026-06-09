# Car Price Prediction using Machine Learning

## Overview

The price of a used car depends on several factors such as vehicle age, fuel type, transmission type, ownership history, and market value. Estimating the correct selling price manually can be challenging due to the influence of multiple variables.

This project develops a Machine Learning-based car price prediction system that estimates the selling price of a vehicle using historical automobile data. Different machine learning techniques were explored, and the best-performing model was selected based on evaluation metrics.

## Objectives

* Analyze factors affecting car prices.
* Perform data preprocessing and feature engineering.
* Train machine learning models for price prediction.
* Compare model performance using evaluation metrics.
* Build a predictive system for estimating used car prices.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Dataset

The dataset contains information about used cars, including:

* Car Name
* Manufacturing Year
* Present Price
* Selling Price
* Kilometers Driven
* Fuel Type
* Selling Type
* Transmission Type
* Number of Previous Owners

## Project Workflow

### 1. Data Loading

The dataset was imported and explored using Pandas.

### 2. Data Exploration

Dataset structure, data types, and missing values were analyzed.

### 3. Feature Engineering

A new feature called **Car_Age** was created from the manufacturing year to better represent vehicle depreciation.

### 4. Data Preprocessing

* Unnecessary columns were removed.
* Categorical variables were converted into numerical format using one-hot encoding.

### 5. Model Training

Two machine learning algorithms were implemented:

* Linear Regression
* Random Forest Regressor

### 6. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

## Results

### Linear Regression

* MAE: 1.216
* MSE: 3.481
* R² Score: 0.849

### Random Forest Regressor

* R² Score: 0.959

The Random Forest model achieved the highest performance and was selected as the final model.

## Key Insights

* Present price is one of the strongest predictors of selling price.
* Vehicle age significantly impacts resale value.
* Fuel type and transmission contribute to price variations.
* Random Forest captured complex relationships more effectively than Linear Regression.

## Files Included

* HarshitMehan_Task3.ipynb
* car_price_prediction_model.pkl
* README.md

## Future Improvements

* Hyperparameter tuning for better performance.
* Integration with real-time automobile market data.
* Development of a web-based prediction application using Flask or Streamlit.

## Author

Harshit Mehan

Oasis Infobyte Data Science Internship
