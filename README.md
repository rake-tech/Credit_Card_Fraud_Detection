💳 Advanced Credit Card Fraud Detection using Machine Learning
📌 Project Overview

This project presents an end-to-end Machine Learning solution for detecting fraudulent credit card transactions using the IEEE-CIS Fraud Detection dataset. The goal is to accurately classify transactions as fraudulent or legitimate by applying data preprocessing, feature engineering, model training, hyperparameter tuning, and model evaluation techniques. The trained model is deployed through a Streamlit web application that enables users to upload transaction data and obtain fraud predictions in real time.

🎯 Objectives
Detect fraudulent credit card transactions with high accuracy.
Perform comprehensive data preprocessing and feature engineering.
Compare multiple Machine Learning algorithms.
Optimize model performance using hyperparameter tuning.
Deploy the trained model through an interactive Streamlit web application.
📂 Dataset

Dataset: IEEE-CIS Fraud Detection Dataset

The dataset contains transaction and identity information collected for fraud detection and includes both numerical and categorical features.

🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
LightGBM
CatBoost
Matplotlib
Seaborn
Plotly
Streamlit
Joblib
🔍 Project Workflow
Data Collection
Data Cleaning
Exploratory Data Analysis (EDA)
Missing Value Handling
Feature Engineering
Feature Selection
Model Training
Hyperparameter Tuning
Model Evaluation
Model Saving
Streamlit Web Application Development
🤖 Machine Learning Models
Logistic Regression
Random Forest Classifier
XGBoost Classifier
LightGBM Classifier
CatBoost Classifier

The best-performing model was selected based on evaluation metrics and saved for deployment.

📊 Model Evaluation

The model performance was evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix
🌐 Streamlit Web Application Features
Interactive Dashboard
CSV File Upload
Batch Fraud Prediction
Fraud Probability Estimation
Model Information
Interactive Charts
Download Prediction Results
📁 Project Structure
IEEE-CIS-Fraud-Detection/
│
├── app.py
├── requirements.txt
├── README.md
├── models/
│   ├── IEEE_fraud_model.pkl
│   ├── feature_columns.pkl
│   └── encoders.pkl
├── sample_data/
└── screenshots/
▶️ How to Run

Install the required packages:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py
📈 Future Enhancements
Real-time fraud detection using APIs
Deep Learning-based fraud detection models
Explainable AI (SHAP/LIME)
Cloud deployment
Automated preprocessing pipeline
Live transaction monitoring dashboard

👨‍💻 Author

Rakesh Nadakuditi

Project: Advanced Credit Card Fraud Detection using Machine Learning
