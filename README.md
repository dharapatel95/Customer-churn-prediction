
# Customer Churn Prediction using ANN

A machine learning web application that predicts whether a bank customer is likely to leave the bank (churn) using an **Artificial Neural Network (ANN)**.

## Project Overview

Customer churn prediction helps businesses identify customers who may stop using their services. This project uses customer information such as credit score, geography, gender, age, balance, salary, and account activity to predict whether a customer will exit the bank.

The trained ANN model is integrated with a Streamlit web application for real-time predictions.

## Features

- Predicts customer churn using an Artificial Neural Network
- User-friendly Streamlit interface
- Performs data preprocessing before prediction
- Uses saved encoders and scaler for consistent input transformation
- Provides churn probability and final prediction result


## Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit


## Project Structure

```text
Customer-churn-prediction/
│
├── app.py                         # Streamlit web application
├── experiments.ipynb              # Model training and experiments
├── prediction.ipynb               # Model prediction notebook
├── model.h5                       # Trained ANN model
├── label_encoder_gender.pkl       # Saved gender label encoder
├── onehot_encoder_geo.pkl         # Saved geography one-hot encoder
├── scaler.pkl                     # Saved feature scaler
├── requirements.txt               # Project dependencies
├── runtime.txt                    # Python runtime version
└── README.md
