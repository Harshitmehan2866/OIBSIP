# Email Spam Detection using Machine Learning

## Overview

Email spam has become a major challenge in digital communication. Spam messages often contain advertisements, scams, phishing links, or unwanted content that can affect users and organizations.

This project develops a Machine Learning-based spam detection system capable of classifying messages as either **Spam** or **Ham (Legitimate Message)**. The model uses Natural Language Processing (NLP) techniques to convert text into numerical features and then applies a classification algorithm to identify spam messages.

## Objectives

* Build an automated spam detection system.
* Perform text preprocessing and feature extraction.
* Train a machine learning model to classify messages.
* Evaluate the model using standard performance metrics.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TF-IDF Vectorization
* Multinomial Naive Bayes

## Dataset

The SMS Spam Collection dataset contains labeled messages categorized as:

* Ham (Legitimate Message)
* Spam (Unwanted Message)

The dataset was used to train and evaluate the classification model.

## Project Workflow

### 1. Data Loading

The dataset was imported into a Pandas DataFrame.

### 2. Data Cleaning

Unnecessary columns were removed and the dataset was prepared for analysis.

### 3. Label Encoding

Text labels were converted into numerical values:

* Ham → 0
* Spam → 1

### 4. Feature Extraction

TF-IDF Vectorization was applied to transform text messages into numerical feature vectors.

### 5. Model Training

A Multinomial Naive Bayes classifier was trained using the processed dataset.

### 6. Model Evaluation

The model was evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Results

### Dataset Split

* Training Samples: 4457
* Testing Samples: 1115

### Model Performance

* Accuracy: 96.86%

### Classification Report

| Class | Precision | Recall | F1-Score |
| ----- | --------- | ------ | -------- |
| Ham   | 0.96      | 1.00   | 0.98     |
| Spam  | 1.00      | 0.77   | 0.87     |

The model successfully classified the majority of spam and legitimate messages with high accuracy.

## Files Included

* HarshitMehan_Task4.ipynb
* spam_detection_model.pkl
* README.md

## Future Improvements

* Apply advanced text preprocessing techniques.
* Experiment with Support Vector Machines and Deep Learning models.
* Develop a web application for real-time spam detection.

## Author

Harshit Mehan

Oasis Infobyte Data Science Internship
