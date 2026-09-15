# Loan Default Prediction Using Machine Learning

A machine learning project for predicting the likelihood of loan default using financial data and multiple classification algorithms.

## 📌 Overview

This project explores machine learning techniques for identifying customers who are at higher risk of loan default.

The workflow includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Feature encoding
- Model training
- Model comparison
- Hyperparameter tuning
- Performance evaluation

## 🤖 Models Used

The project evaluates three classification algorithms:

- Random Forest
- Support Vector Machine (SVM)
- XGBoost

## 📊 Results

The models were evaluated using classification performance metrics.

XGBoost achieved:

- **91% Accuracy**
- **0.94 AUC-ROC**

The project was developed using a dataset containing more than **225,000 loan records**.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Project Structure

```text
loan-default-prediction/
│
├── Loan_Default_Train_Save.ipynb
├── t.ipynb
│
├── feature_columns.pkl
├── label_encoders.pkl
├── svm_model.pkl
└── xgb_model.pkl
