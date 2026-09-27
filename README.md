# CarWise - Car Purchase Decision Prediction

CarWise is a Machine Learning project that predicts whether a car should be **BUY (1)** or **AVOID (0)** based on its features.

## Project Overview

The project uses **Logistic Regression** to classify cars into two categories:

- `1` → BUY
- `0` → AVOID

The target is created using the median **Price** and **Mileage** of the dataset. A car is classified as BUY when both its price and mileage are at or below their respective median values.

## Workflow

Dataset → Data Cleaning → Categorical Encoding → 80/20 Train-Test Split → Feature Scaling → Custom Logistic Regression → Evaluation

## Key Features

- Data cleaning and preprocessing
- Label Encoding for categorical features
- Manual 80/20 Train-Test Split
- Feature Standardization
- Custom Logistic Regression implemented using NumPy
- Gradient Descent optimization
- Manual evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

## Technologies

- Python
- NumPy
- Pandas
- Jupyter Notebook / Google Colab

## Model

A custom Logistic Regression model was implemented from scratch using:

- Sigmoid activation
- Gradient Descent
- Learning Rate: `0.01`
- Epochs: `2500`

## Purpose

This project demonstrates the complete Machine Learning workflow, from data preprocessing and feature engineering to model training and performance evaluation.
