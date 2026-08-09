# Red Wine Quality Prediction Using Random Forest

## Project Overview

This project predicts **red wine quality** using **Random Forest**, an ensemble learning technique based on multiple Decision Trees. The objective is to analyze the physicochemical properties of red wine and classify wine quality ratings using a Random Forest Classifier.

## Dataset

The dataset contains physicochemical properties of red wine along with their quality ratings.

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
- Quality

### Dataset Size

- **1,599 Records**
- **11 Features**
- **1 Target Variable**

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Random Forest Classifier

## Project Workflow

- Data Loading
- Data Exploration
- Descriptive Statistical Analysis
- Missing Value Checking
- Data Visualization
- Correlation Analysis
- Feature and Target Separation
- Train-Test Split
- Random Forest Model Building
- Model Training
- Model Prediction
- Model Evaluation
- Conclusion

## Key Concepts Covered

- Supervised Learning
- Classification
- Random Forest
- Ensemble Learning
- Decision Trees
- Train-Test Split
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Model Evaluation
- Overfitting

## Evaluation Metrics

The Random Forest model is evaluated using:

- **Accuracy:** Measures the percentage of correctly classified wine quality ratings.
- **Confusion Matrix:** Shows the correct and incorrect predictions for each wine quality class.
- **Precision:** Measures the proportion of correctly predicted positive observations.
- **Recall:** Measures how effectively the model identifies actual positive observations.
- **F1-Score:** Provides a balance between precision and recall.
- **Classification Report:** Provides a detailed summary of precision, recall, F1-score, and support for each class.

## Results

The Random Forest model achieved:

- **Training Accuracy: 100%**
- **Testing Accuracy: 65.94%**

The difference between training and testing accuracy indicates that the model performs extremely well on the training data but has lower performance on unseen data. This highlights the importance of evaluating model generalization and identifying potential overfitting.

## Project Files

- `Red_Wine_Quality_Prediction_Using_Random_Forest.ipynb`
- `winequality-red.csv`

## Author

**Kayathiri Murugan Konar**

## Connect With Me

LinkedIn: https://www.linkedin.com/in/kayathiri-m-konar-a020b929a/

GitHub: https://github.com/kayathirimkonar14-source
