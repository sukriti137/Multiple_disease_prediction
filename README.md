# 🏥 Disease Prediction System

An ML-powered web application built with **Streamlit** that predicts the likelihood of multiple diseases using patient health parameters.

---

## 🚀 Overview

The Disease Prediction System is a machine learning-based healthcare application designed to assist in the early detection of diseases by analyzing user-provided medical information.

The system currently supports prediction for:

* Diabetes
* Heart Disease
* Parkinson's Disease

The application provides a simple and interactive interface where users can enter medical parameters and receive instant predictions.

---

## 🎯 Problem Statement

Early detection of diseases can significantly improve treatment outcomes and reduce healthcare costs. However, many individuals do not have immediate access to preliminary health risk assessments.

This project aims to provide a quick and accessible disease risk prediction tool using machine learning models trained on publicly available healthcare datasets.

---

## 💡 Solution

The application leverages machine learning models trained on disease-specific datasets to predict whether a patient is likely to have a particular disease based on medical inputs.

Users can:

* Enter health-related parameters
* Select a disease prediction module
* Receive instant prediction results
* Use the application through an easy-to-use web interface

---

## 🛠️ Tech Stack

### Frontend

* Streamlit
* HTML/CSS (Streamlit Styling)

### Backend

* Python

### Machine Learning

* Scikit-Learn
* Logistic Regression
* Support Vector Machine (SVM)

### Data Processing

* NumPy
* Pandas

### Model Storage

* Pickle (.sav files)

---

## 📂 Project Structure

```text
Disease-Prediction-System/
│
├── colab_files_to_train_models/
│   ├── Daibetes Prediction.ipynb
│   ├── Heart Disease.ipynb
│   └── Parkinson's Disease Detection.ipynb
│
├── dataset/
│   ├── diabetes.csv
│   ├── heart_disease_data.csv
│   └── parkinsons.csv
│
├── saved_models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
├── README.md
├── app.py
└── requirements.txt
```


## 🧠 Machine Learning Models

| Disease             | Algorithm Used               |
| ------------------- | ---------------------------- |
| Diabetes            | Support Vector Machine (SVM) |
| Heart Disease       | Logistic Regression          |
| Parkinson's Disease | Support Vector Machine (SVM) |

The models were trained using disease-specific datasets and saved using Python's Pickle library for deployment.

---

## 📊 Features

* ✅ Multi-Disease Prediction
* ✅ Interactive Streamlit Dashboard
* ✅ Instant Prediction Results
* ✅ Pre-trained Machine Learning Models
* ✅ User-Friendly Interface
* ✅ Lightweight and Fast Deployment

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/sukriti137/Multiple_disease_prediction.git
cd Multiple_disease_prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📌 Future Enhancements

* Add more disease prediction modules
* Improve model accuracy using advanced algorithms
* Integrate user authentication
* Store prediction history
* Deploy on cloud platforms
* Add visualization of patient health data

---

## 📄 License

This project is developed for educational purposes and demonstrates the application of machine learning in healthcare.
