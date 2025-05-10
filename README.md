# KDD Anomaly Detection with Machine Learning

This project uses the KDD Cup 1999 dataset to build an anomaly detection system for identifying malicious network traffic. Several machine learning models are trained and evaluated to classify network activity as either normal or an attack.

## Features

- Loads and preprocesses the KDD dataset
- Label encodes categorical features and normalizes numerical data
- Trains multiple classifiers including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
- Evaluates each model with accuracy, confusion matrix, and classification report
- Visualizes attack class distribution and model performance using plots

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt



