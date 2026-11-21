#  Heart Disease Prediction Using Machine Learning

A Machine Learning-based Heart Disease Prediction application built using **Python, Scikit-learn, K-Nearest Neighbors (KNN), and Streamlit**. The application allows users to enter health-related parameters and receive a model prediction through an interactive web interface.

<img width="1798" height="911" alt="image" src="https://github.com/user-attachments/assets/19c25ad4-87e2-4630-a3ac-613cbabcd987" />


## 🚀 Project Overview

This project uses a trained KNN classification model to predict whether a person is likely to have heart disease based on selected clinical and health-related features.

The model is integrated into a Streamlit web application, allowing users to enter their details and get predictions without directly interacting with Python code.

## ✨ Features

- Interactive web interface built with Streamlit.
- Heart disease prediction using K-Nearest Neighbors (KNN).
- Data preprocessing and feature encoding.
- Feature scaling using StandardScaler.
- One-hot encoding for categorical variables.
- Model serialization and loading using Joblib.
- Prediction output with a simple visual interface.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computations |
| Scikit-learn | Machine Learning |
| KNN | Classification algorithm |
| StandardScaler | Feature scaling |
| Joblib | Model serialization |
| Streamlit | Web application |

## 📂 Project Structure

```text
Heart-Disease-Predictor/
│
├── app.py
├── heart Problem predictor.ipynb
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└── README.md
```

## 📊 Input Features

The application collects the following information:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

## ⚙️ Machine Learning Workflow

1. Load and explore the heart disease dataset.
2. Perform data cleaning and preprocessing.
3. Handle categorical features using One-Hot Encoding.
4. Scale numerical features using StandardScaler.
5. Train a K-Nearest Neighbors classification model.
6. Save the trained model and preprocessing objects using Joblib.
7. Load the saved model into the Streamlit application.
8. Process user inputs and generate predictions.


## ⚠️ Disclaimer

This project is developed for educational and machine learning demonstration purposes only. Predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.

## 👨‍💻 Author

**Parth Thapliyal**
