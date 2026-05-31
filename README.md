Heart Stroke Prediction
Overview

This project is a Machine Learning-powered web application that predicts the likelihood of heart disease based on patient medical information. Multiple classification algorithms were trained and evaluated, including K-Nearest Neighbors (KNN), Decision Tree, Random Forest, Support Vector Machine (SVM), and Logistic Regression.

Among all tested models, Logistic Regression achieved the highest accuracy and was selected as the final model for deployment.

The application is built using Streamlit, providing an interactive and user-friendly interface for real-time predictions.

Features
Predicts heart disease risk using patient health parameters
Interactive web interface built with Streamlit
Multiple machine learning models evaluated
Logistic Regression selected as the best-performing model
Real-time prediction results
Data preprocessing and feature scaling included
Technologies Used
Machine Learning
Python
Scikit-learn
Pandas
NumPy
Frontend & Deployment
Streamlit
Model Persistence
Joblib
Machine Learning Models Evaluated

The following classification algorithms were trained and compared:

Logistic Regression ✅
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)

After evaluation, Logistic Regression provided the best accuracy and generalization performance, making it the final model used for prediction.

Dataset Features

The model uses the following patient attributes:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate
Exercise-Induced Angina
Oldpeak (ST Depression)
ST Slope
Project Structure
Heart-Disease-Prediction/
│
├── app.py
├── logistic_regression_heart.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── requirements.txt
├── README.md
│
└── dataset/
    └── heart.csv
