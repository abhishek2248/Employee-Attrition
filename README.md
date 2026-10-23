# Employee Attrition Prediction Using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations because employee turnover can increase recruitment costs, training expenses, and workload on existing employees.

This project uses Machine Learning classification algorithms to predict whether an employee is likely to leave an organization. The project uses the IBM HR Employee Attrition dataset and applies data preprocessing, exploratory data analysis (EDA), data visualization, feature scaling, model training, and evaluation.

## 🎯 Objectives

- Analyze employee data to understand patterns related to attrition.
- Perform Exploratory Data Analysis (EDA) to identify important trends and relationships.
- Clean and preprocess the dataset for machine learning.
- Convert categorical variables into numerical features using one-hot encoding.
- Apply feature scaling using StandardScaler.
- Train and evaluate multiple classification algorithms.
- Compare model performance using accuracy, confusion matrices, classification reports, and cross-validation.
- Apply GridSearchCV to tune model hyperparameters.
- Use Principal Component Analysis (PCA) to reduce dimensionality.
- Identify a suitable classification model for employee attrition prediction.

## ❗ Problem Statement

Employee attrition can negatively affect an organization's productivity, employee retention, and operational costs. Organizations need a way to identify employees who may be at risk of leaving.

The objective of this project is to develop a Machine Learning classification model that predicts employee attrition using available HR data. The model analyzes employee-related features and classifies employees into two categories: **Attrition (Yes)** and **No Attrition (No)**.

The predictions can help HR teams understand attrition patterns and support data-driven employee retention strategies.

## 📊 Dataset

- **Dataset:** IBM HR Employee Attrition
- **Source:** [Kaggle – HR Employee Attrition Dataset](https://www.kaggle.com/datasets/itssuru/hr-employee-attrition/data)
- **Target variable:** `Attrition`
- **Target encoding:** Yes = 1, No = 0

The dataset contains employee-related information, including age, department, job role, monthly income, job satisfaction, business travel, overtime, and other HR attributes.

## 🛠️ Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Check dataset dimensions, data types, missing values, and unique values.
4. Remove irrelevant and constant columns.
5. Perform exploratory data analysis and data visualization.
6. Convert the target variable into numerical values.
7. Encode categorical features using `pd.get_dummies()`.
8. Separate the input features (X) and target variable (y).
9. Apply feature scaling using `StandardScaler`.
10. Split the data into training and testing sets.
11. Train multiple Machine Learning classification models.
12. Tune model hyperparameters using `GridSearchCV`.
13. Evaluate and compare model performance.
14. Apply PCA for dimensionality reduction and evaluate a Random Forest model.

## 🤖 Machine Learning Algorithms

The project implements the following classification algorithms:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- AdaBoost Classifier

Random Forest hyperparameters are optimized using GridSearchCV. PCA is also explored with a Random Forest classifier.

## 📈 Model Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Cross-Validation Score

These metrics help evaluate the classification models and compare their performance.

## 💡 Expected Outcome

The project aims to develop a model that can classify employee attrition and help identify patterns associated with employees leaving an organization.

The model's actual performance should be determined from the evaluation results produced by the notebook.

## 🚀 Future Improvements

- Address class imbalance to improve the detection of employees who leave.
- Compare additional classification algorithms.
- Improve model evaluation using ROC-AUC and precision-recall metrics.
- Use feature importance and explainability techniques to understand key attrition factors.
- Deploy the trained model through a simple web application.
- Provide predictions for new employee records.

## 👨‍💻 Project Type

Machine Learning | Classification | Human Resources Analytics | Data Science
