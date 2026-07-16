🏥 Disease Prediction System
An ML-powered web application built with Streamlit that predicts the likelihood of multiple diseases using patient health parameters.

🚀 Overview
The Disease Prediction System is a machine learning-based healthcare application designed to assist in the early detection of diseases by analyzing user-provided medical information.

The system currently supports prediction for:

Diabetes
Heart Disease
Parkinson's Disease
The application provides a simple and interactive interface where users can enter medical parameters and receive instant predictions.

🎯 Problem Statement
Early detection of diseases can significantly improve treatment outcomes and reduce healthcare costs. However, many individuals do not have immediate access to preliminary health risk assessments.

This project aims to provide a quick and accessible disease risk prediction tool using machine learning models trained on publicly available healthcare datasets.

💡 Solution
The application leverages Logistic Regression models trained on disease-specific datasets to predict whether a patient is likely to have a particular disease based on medical inputs.

Users can:

Enter health-related parameters
Select a disease prediction module
Receive instant prediction results
Use the application through an easy-to-use web interface
🛠️ Tech Stack
Frontend
Streamlit
HTML/CSS (Streamlit Styling)
Backend
Python
Machine Learning
Scikit-Learn
Logistic Regression
Support Vector Machine Model
Data Processing
NumPy
Pandas
Model Storage
Pickle (.sav files)
📂 Project Structure
Disease-Prediction-System/
│
├── saved models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
├── diabetes.csv
├── heart.csv
├── parkinsons.csv
│
├── app.py
├── requirements.txt
└── README.md
🧠 Machine Learning Models
Disease	Algorithm Used
Diabetes	Support Vector Machine Model
Heart Disease	Logistic Regression
Parkinson's Disease	Support Vector Machine Model
The models were trained using disease-specific datasets and saved using Python's Pickle library for deployment.

📊 Features
✅ Multi-Disease Prediction

✅ Interactive Streamlit Dashboard

✅ Instant Prediction Results

✅ Pre-trained Machine Learning Models

✅ User-Friendly Interface

✅ Lightweight and Fast Deployment
