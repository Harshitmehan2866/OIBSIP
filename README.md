# Car Price Prediction Using Machine Learning

## Overview

This project focuses on predicting the selling price of used cars using machine learning techniques. The objective is to develop a model that can estimate the market value of a vehicle based on its characteristics such as age, fuel type, transmission type, ownership history, and present price.

The project was completed as part of the Oasis Infobyte Data Science Internship program.

## Dataset Description

The dataset contains information about previously owned vehicles, including:

* Car Name
* Manufacturing Year
* Selling Price
* Present Price
* Kilometers Driven
* Fuel Type
* Selling Type
* Transmission Type
* Number of Previous Owners

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Project Workflow

### 1. Data Collection

The dataset was loaded into a Pandas DataFrame for analysis and preprocessing.

### 2. Data Exploration

The dataset structure, feature types, and missing values were examined to understand the available information.

### 3. Feature Engineering

A new feature named **Car_Age** was created from the manufacturing year to better represent vehicle depreciation.

### 4. Data Preprocessing

Categorical variables were converted into numerical form using one-hot encoding.

### 5. Model Training

Two machine learning algorithms were implemented:

* Linear Regression
* Random Forest Regressor

### 6. Model Evaluation

The models were evaluated using:

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

The Random Forest model produced the best performance and was selected as the final model.

## Key Insights

* Present price is one of the strongest indicators of selling price.
* Vehicle age has a significant impact on resale value.
* Fuel type and transmission influence market pricing.
* Random Forest captured non-linear relationships more effectively than Linear Regression.

## Files Included

* HarshitMehan_Task3.ipynb
* car_price_prediction_model.pkl
* README.md

## Future Improvements

* Hyperparameter tuning for improved accuracy.
* Deployment using Flask or Streamlit.
* Integration with real-time automobile market data.

## Author

Harshit Mehan

Oasis Infobyte Data Science Internship
