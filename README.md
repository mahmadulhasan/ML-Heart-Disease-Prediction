# Heart Disease Prediction

A machine learning project that predicts heart disease presence using patient health metrics. The dataset contains 918 medical records with 11 clinical features.

## Overview

This project implements and compares 5 classification algorithms to predict the presence of heart disease based on patient health indicators.

## Dataset

- **Size:** 918 patient records
- **Features:** 11 clinical metrics (age, sex, blood pressure, cholesterol, chest pain type, etc.)
- **Target:** Heart disease presence (binary classification)

## Models Evaluated

- Logistic Regression (85.33% accuracy)
- K-Nearest Neighbors (84.78% accuracy)
- Naive Bayes (86.41% accuracy)
- Decision Tree (79.89% accuracy)
- **SVM (88.04% accuracy)** ✓ Best performer

## Key Features

- Data preprocessing and feature engineering
- One-hot encoding for categorical variables
- Feature scaling with StandardScaler
- Train-test split (80-20)
- Model evaluation using Accuracy and F1-Score
- Serialized models for deployment

## Technologies

Python, Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib

<img width="1920" height="1422" alt="screencapture-localhost-8501-2026-06-12-15_58_40" src="https://github.com/user-attachments/assets/c4ef0f80-dc75-477b-9950-52b02cef4ad6" />
