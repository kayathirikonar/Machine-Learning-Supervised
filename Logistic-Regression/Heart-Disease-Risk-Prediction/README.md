# Heart Disease Risk Prediction using Logistic Regression

## Project Overview

This project predicts the risk of **heart disease** using **Logistic Regression**, a supervised machine learning classification algorithm. The objective is to analyze health-related and lifestyle factors and build a model that can classify whether an individual is likely to have heart disease.

The project focuses on data exploration, data cleaning, feature selection, categorical data encoding, visualization, model training, and classification model evaluation.

---

## Dataset

The dataset contains health, lifestyle, and demographic information of individuals.

### Key Features

- **BMI:** Body Mass Index
- **Smoking:** Whether the individual has a history of smoking
- **AlcoholDrinking:** Whether the individual consumes heavy amounts of alcohol
- **Stroke:** Whether the individual has previously experienced a stroke
- **Sex:** Gender of the individual
- **Diabetic:** Diabetes status
- **Asthma:** Whether the individual has asthma
- **KidneyDisease:** Whether the individual has kidney disease
- **SkinCancer:** Whether the individual has a history of skin cancer
- **SleepTime:** Average number of hours of sleep
- **HeartDisease:** Target variable indicating whether the individual has heart disease

### Dataset Size

- **319,795 Records**
- **18 Columns**
- **17 Input Features**
- **1 Target Variable**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Logistic Regression

---

## Project Workflow

- Data Collection
- Data Loading and Exploration
- Tabular Analysis
- Missing Value Detection and Handling
- Data Cleaning
- Feature Selection
- Categorical Data Encoding
- Data Visualization
- Train-Test Split
- Logistic Regression Model Building
- Model Prediction
- Model Evaluation
- Conclusion

---

## Key Concepts Covered

- Binary Classification
- Logistic Regression
- Data Cleaning
- Exploratory Data Analysis
- Feature Selection
- Categorical Encoding
- Data Preprocessing
- Train-Test Split
- Classification Model Evaluation
- Health Risk Prediction

---

## Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for binary classification problems.

In this project, the model predicts:

- **1 → Heart Disease**
- **0 → No Heart Disease**

The dataset is divided into:

- **80% Training Data**
- **20% Testing Data**

The model is trained using the training dataset and evaluated on unseen testing data.

---

## Evaluation Metrics

The Logistic Regression model is evaluated using a **Classification Report**, which provides the following metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how effectively the model identifies actual positive cases.
- **F1-Score:** Provides a balance between Precision and Recall.
- **Support:** Represents the number of actual observations belonging to each class.

These metrics provide a more detailed understanding of classification performance than accuracy alone.

---

## Results

The Logistic Regression model provides a baseline approach for predicting heart disease risk from health-related and lifestyle features.

The classification report is used to evaluate the model's **precision, recall, F1-score, and overall classification performance** on the test dataset.

The project demonstrates how appropriate data preprocessing, feature selection, categorical encoding, and classification techniques can be combined to build a machine learning model for health-related prediction.

---

## Project Files

- **Heart_Disease_Risk_Prediction_Logistic_Regression.ipynb**
- **heart.csv**

---

## Author

**Kayathiri Murugan Konar**

---

## Connect With Me

**LinkedIn:**  
https://www.linkedin.com/in/kayathiri-m-konar-a020b929a/

**GitHub:**  
https://github.com/kayathirimkonar14-source
