Heart Disease Prediction using Machine Learning
Project Overview

This project builds a binary classification machine learning model to predict whether a person has heart disease based on medical and lifestyle features.
The model is developed using Logistic Regression and follows a complete machine learning workflow including data preprocessing, feature encoding, scaling, model training, evaluation, and exploratory data analysis (EDA).

Problem Statement

Heart disease is one of the major health risks worldwide.
The goal of this project is to use patient data such as age, cholesterol level, heart rate, stress level, smoking habits, and alcohol intake to predict the probability of heart disease.

Dataset

The dataset used in this project is a synthetic heart disease dataset containing multiple patient attributes.

Example Features

Age

Gender

Heart Rate

Smoking Status

Stress Level

Cholesterol Total

Alcohol Intake

Other medical indicators

Target Variable

Heart_Disease

0 → No disease

1 → Disease present

Machine Learning Workflow
1. Data Loading

Dataset is loaded using Pandas.

2. Data Cleaning

Missing values checked using isnull()

Missing categorical values handled using "Unknown" category

3. Feature and Target Separation

Independent variables → X

Dependent variable → y

4. Categorical Encoding

One-Hot Encoding applied using ColumnTransformer

Converts text categories into numerical format

5. Train-Test Split

Dataset split into 70% training and 30% testing

Ensures model evaluation on unseen data

6. Feature Scaling

StandardScaler used to standardize feature values

Improves convergence and model performance

7. Model Training

Logistic Regression model used for binary classification

Learns relationship between patient features and disease risk

8. Prediction

Model predicts disease presence on test dataset

9. Model Evaluation

Performance measured using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

10. Exploratory Data Analysis

Scatter plots to analyze feature-target relationship

Correlation heatmap to detect strong predictors and multicollinearity

Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Results

The Logistic Regression model successfully learns patterns from patient data and predicts heart disease status with measurable classification performance.

How to Run

Clone the repository

git clone https://github.com/yourusername/heart-disease-prediction.git

Install required libraries

pip install numpy pandas matplotlib seaborn scikit-learn

Open the Jupyter Notebook

jupyter notebook

Run all cells sequentially

Future Improvements

Try advanced models (Random Forest, XGBoost, SVM)

Perform hyperparameter tuning

Handle class imbalance

Build a deployment interface (Streamlit / Flask)

Improve feature engineering

Author

Vishal

License

This project is for educational and learning purposes.
