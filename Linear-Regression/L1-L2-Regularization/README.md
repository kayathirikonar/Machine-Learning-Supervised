# Comparison of Linear Regression, Lasso Regression, and Ridge Regression

## Project Overview

This project compares the performance of **Linear Regression**, **Lasso Regression (L1 Regularization)**, and **Ridge Regression (L2 Regularization)** for predicting house prices. The objective is to understand how regularization techniques improve model performance by reducing overfitting and enhancing generalization.

---

## Dataset

The dataset contains house-related features, including:

- Size
- Bedrooms
- Age
- Distance
- Noise
- Price (Target Variable)

### Dataset Size

- **10 Records**
- **5 Input Features**
- **1 Target Variable**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Workflow

- Data Collection
- Data Loading and Exploration
- Data Preprocessing
- Train-Test Split
- Linear Regression Model Building
- Lasso Regression (L1 Regularization)
- Ridge Regression (L2 Regularization)
- Model Evaluation using Mean Squared Error (MSE)
- Performance Comparison and Analysis

---

## Key Concepts Covered

- Multiple Linear Regression
- Regularization
- L1 Regularization (Lasso)
- L2 Regularization (Ridge)
- Overfitting and Underfitting
- Mean Squared Error (MSE)
- Model Performance Comparison

---

## Models Implemented

### Linear Regression
A baseline regression model that predicts house prices without applying any regularization.

### Lasso Regression (L1 Regularization)
Applies an L1 penalty to shrink less important feature coefficients toward zero, which can also perform feature selection.

### Ridge Regression (L2 Regularization)
Applies an L2 penalty to reduce the magnitude of coefficients, helping improve model stability and reduce overfitting.

---

## Evaluation Metric

The models are evaluated using:

- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted house prices. Lower MSE indicates better model performance.

---

## Results

The project demonstrates how Lasso and Ridge Regression improve the robustness of regression models by controlling coefficient values through regularization. Comparing the MSE values of all three models provides insights into the effectiveness of each approach for house price prediction.

---

## Project Files

- **Comparison_of_Linear_Lasso_and_Ridge_Regression.ipynb**
- **house_data.csv**

---

## Author

**Kayathiri Murugan Konar**

---

## Connect With Me

**LinkedIn:** https://www.linkedin.com/in/kayathiri-m-konar-a020b929a/

**GitHub:** https://github.com/kayathirimkonar14-source
