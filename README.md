# wine-quality-prediction
Machine Learning model to predict red wine quality using physicochemical properties
# Wine Quality Prediction 🍷

A machine learning project that predicts red wine quality based on physicochemical properties using multiple classification algorithms.

## 📊 Project Overview

This project transforms wine quality ratings into a binary classification problem, categorizing wines as either "good" or "bad" based on 11 chemical features including acidity levels, pH, alcohol content, and more.

## 🎯 Objective

Predict wine quality using:
- **Fixed Acidity, Volatile Acidity, Citric Acid**
- **Residual Sugar, Chlorides**
- **Free & Total Sulfur Dioxide**
- **Density, pH, Sulphates, Alcohol**

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine learning algorithms
- **Seaborn/Matplotlib** - Data visualization
- **Jupyter Notebook** - Development environment

## 🤖 Machine Learning Models

| Algorithm | Configuration | Performance |
|-----------|---------------|-------------|
| **Random Forest** | 200 estimators | ⭐ Best Performer |
| **SVM** | RBF kernel | Good |
| **Neural Network** | 3 hidden layers (11 neurons each) | Decent |

## 📈 Key Results

- **Binary Classification**: Good vs Bad wine quality
- **Data Processing**: StandardScaler normalization, 80-20 train-test split
- **Evaluation Metrics**: Classification report, Confusion matrix
- **Best Model**: Random Forest (handles feature interactions effectively)

