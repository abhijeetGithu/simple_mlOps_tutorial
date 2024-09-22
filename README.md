

# 🍷 Wine Quality Predictor

![Alt text](./Screenshot%202024-09-08%20233250.png)
A Website Url link-- https://wine-abstar-0cf360594a75.herokuapp.com/

## Overview

**Wine Quality Predictor** is an MLOps-powered application designed to predict the quality of wine based on its chemical properties. By leveraging machine learning, this platform streamlines the process of training, deploying, and monitoring models in a reproducible and scalable manner.

This project demonstrates the end-to-end MLOps lifecycle: from data ingestion and model training to deployment and monitoring, while integrating modern tools like Docker, MLflow, and CI/CD pipelines.

---

## 🚀 Features

- **Accurate Predictions**: Predicts wine quality based on multiple features like acidity, alcohol content, pH, etc.
- **Automated Workflows**: Fully automated training, testing, and deployment pipelines.
- **Version Control**: Model versioning using `MLflow` to track experiments and results.
- **Scalable Deployment**: Containerized using Docker, deployed on AWS/Heroku.
- **Continuous Integration**: Ensures code quality and integrity with integrated CI/CD pipelines.

---

## 📁 Project Structure

```bash
wine-quality-predictor/
├── data/
│   ├── winequality-red.csv         # Red wine data
│   └── winequality-white.csv       # White wine data
├── models/
│   └── model.pkl                   # Trained ML model
├── notebooks/
│   ├── EDA.ipynb                   # Exploratory Data Analysis notebook
│   └── model_training.ipynb        # Model training and evaluation
├── scripts/
│   ├── data_preprocessing.py       # Data cleaning and preprocessing script
│   └── model_train.py              # Model training script
├── Dockerfile                      # Docker setup for deployment
├── requirements.txt                # Python dependencies
├── mlflow_setup.py                 # MLflow experiment setup
├── app.py                          # Streamlit app for wine prediction
├── README.md                       # Project documentation
└── .github/
    └── workflows/
        └── ci.yml                  # CI/CD pipeline configuration
