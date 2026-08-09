# Wine Quality Prediction Using Bagged Decision Trees

## Project Overview

This project predicts red wine quality using **Bagged Decision Trees**, an ensemble learning technique based on Bootstrap Aggregation (Bagging). The objective is to analyze the physicochemical properties of red wine and classify wine quality using an ensemble of Decision Tree models.

## Dataset

The dataset contains physicochemical properties of red wine and its quality rating.

The dataset includes the following features:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

**Target Variable:**
- Quality: Wine quality rating

### Dataset Size

- 1,599 Records
- 11 Features
- 1 Target Variable

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Decision Tree Classifier
- Bagging Classifier

## Project Workflow

- Data Loading
- Data Exploration
- Descriptive Statistical Analysis
- Data Visualization
- Correlation Analysis
- Feature and Target Separation
- Train-Test Split
- Decision Tree Model Building
- Bagging Ensemble Model Building
- Model Prediction
- Model Evaluation
- Conclusion

## Key Concepts Covered

- Supervised Learning
- Classification
- Decision Trees
- Ensemble Learning
- Bagging
- Bootstrap Aggregation
- Train-Test Split
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- Model Evaluation
- Overfitting

## Evaluation Metrics

The model performance is evaluated using:

- **Accuracy:** Measures the percentage of correctly classified wine quality ratings.
- **Confusion Matrix:** Shows the correct and incorrect predictions for each quality class.
- **Precision:** Measures the proportion of correctly predicted positive observations.
- **Recall:** Measures how effectively the model identifies actual positive observations.
- **F1-Score:** Provides a balance between precision and recall.

## Results

The Bagged Decision Tree model achieved **100% training accuracy** and **62.81% testing accuracy**.

The difference between training and testing accuracy indicates that the model performs extremely well on the training data but has lower performance on unseen data, highlighting the importance of evaluating model generalization.

## Project Files

- `Wine_Quality_Prediction_Bagged_Decision_Trees.ipynb`
- `winequality-red.csv`

## Author

**Kayathiri Murugan Konar**

## Connect With Me

LinkedIn: https://www.linkedin.com/in/kayathiri-m-konar-a020b929a/

GitHub: https://github.com/kayathirimkonar14-source
