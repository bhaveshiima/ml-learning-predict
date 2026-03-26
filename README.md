## Diabetes Prediction Model (Machine Learning + Flask)

A Machine Learning-based web application that predicts whether a person has diabetes based on health parameters such as age, BMI, glucose level, and more.

The model is deployed using Flask and served via Gunicorn for production.

## Project Overview

This project demonstrates an end-to-end ML deployment pipeline:

Collect user health data
Process input using NumPy
Predict using trained ML model
Return result via API

## 🛠️ Tech Stack
Backend: Flask
Server: Gunicorn
ML Library: Scikit-learn
Data Processing: Pandas, NumPy
Model Storage: Joblib

## 📂 Project Structure
diabetes-prediction/
│
├── app.py                  # Flask API
├── model.pkl              # Trained ML model
├── label_encoder.pkl      # Smoking encoder (if used)
├── requirements.txt
└── README.md


Source: https://www.udemy.com/course/deploy-machine-learning-models-build-ai-agents-using-n8n/ Created by Vijayarajan Ramanathan
