# 💳 Advanced Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

The **Advanced Credit Card Fraud Detection** project is an end-to-end Machine Learning application developed to identify fraudulent credit card transactions using the **IEEE-CIS Fraud Detection Dataset**. The project demonstrates the complete machine learning lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, feature selection, model training, hyperparameter tuning, model evaluation, model serialization, and deployment through a professional **Streamlit web application**.

The primary objective of this project is to build a highly accurate fraud detection system capable of distinguishing between legitimate and fraudulent transactions while providing an easy-to-use web interface for batch prediction and result visualization.

---

# 🎯 Objectives

- Develop an accurate machine learning model for fraud detection.
- Analyze and preprocess large-scale financial transaction data.
- Handle missing values and optimize feature quality.
- Perform feature engineering and feature selection.
- Train and compare multiple machine learning algorithms.
- Optimize model performance using hyperparameter tuning.
- Evaluate the model using multiple classification metrics.
- Deploy the trained model through an interactive Streamlit web application.
- Provide batch prediction functionality using uploaded CSV files.
- Generate downloadable prediction reports.

---

# 📂 Dataset

**Dataset Name:** IEEE-CIS Fraud Detection Dataset

The IEEE-CIS Fraud Detection dataset is a real-world financial transaction dataset designed for detecting fraudulent credit card transactions. It contains a large number of transaction-related and identity-related features with both numerical and categorical attributes.

### Dataset Files

- train_transaction.csv
- train_identity.csv
- test_transaction.csv
- test_identity.csv

---

# 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Plotly
- Streamlit
- Joblib

### Development Environment

- Google Colab
- Visual Studio Code
- GitHub

---

# 🔄 Project Workflow

## 1. Data Collection

- Loaded the IEEE-CIS Fraud Detection Dataset.
- Imported transaction and identity datasets.
- Merged and analyzed required features.

---

## 2. Data Preprocessing

Performed complete preprocessing including:

- Handling missing values
- Removing unnecessary columns
- Data cleaning
- Feature encoding
- Data transformation
- Memory optimization

---

## 3. Exploratory Data Analysis (EDA)

Performed extensive EDA to understand the dataset.

### Analysis Included

- Missing value analysis
- Class imbalance visualization
- Fraud distribution
- Transaction amount analysis
- Correlation analysis
- Feature distributions
- Statistical summaries

Visualization tools used:

- Bar Charts
- Pie Charts
- Histograms
- Heatmaps
- Count Plots

---

## 4. Feature Engineering

Created meaningful features to improve model performance.

Included:

- Data transformation
- Feature encoding
- Numerical feature optimization
- Categorical feature encoding

---

## 5. Feature Selection

Selected the most important features used for training the model to improve prediction performance and reduce computational complexity.

---

## 6. Machine Learning Model Training

Multiple machine learning algorithms were implemented and compared.

Models trained include:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- LightGBM Classifier
- CatBoost Classifier

The best-performing model was selected for deployment.

---

## 7. Hyperparameter Tuning

Optimized model performance using hyperparameter tuning techniques to improve accuracy and generalization.

---

## 8. Model Evaluation

Model performance was evaluated using several classification metrics.

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

These metrics were used to compare the performance of different algorithms and select the final model.

---

## 9. Model Serialization

The trained model and required files were saved using Joblib.

Saved Files:

- IEEE_fraud_model.pkl
- feature_columns.pkl
- encoders.pkl

These files are used during deployment to perform fraud prediction without retraining the model.

---

# 🌐 Streamlit Web Application

A professional web application was developed using Streamlit.

## Application Features

- Professional Dashboard
- Interactive User Interface
- CSV File Upload
- Batch Fraud Prediction
- Fraud Probability Prediction
- Model Information
- Interactive Charts
- Download Prediction Results
- User-Friendly Navigation

---

# 📊 Dashboard Features

The dashboard includes:

- Model Status
- Dataset Information
- Total Features
- Prediction Statistics
- Interactive Visualizations
- Fraud Distribution Charts

-Home Page 
<img width="1600" height="728" alt="image" src="https://github.com/user-attachments/assets/c5f7ee0c-d802-4998-b889-b61df279039f" />

Prediction
<img width="1600" height="732" alt="image" src="https://github.com/user-attachments/assets/809def84-cce8-4e83-92ee-2f516bfdecf5" />

Dashboard
<img width="1592" height="740" alt="image" src="https://github.com/user-attachments/assets/1c6f0f77-416f-46c5-bdc7-bd5708394183" />

Model Information
<img width="1600" height="732" alt="image" src="https://github.com/user-attachments/assets/4f5917d2-ab58-4f9b-bffa-8846063eb826" />

---

# 📁 Project Structure

```
IEEE-CIS-Fraud-Detection/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   ├── IEEE_fraud_model.pkl
│   ├── feature_columns.pkl
│   └── encoders.pkl
│
├── sample_data/
│   └── demo_transactions.csv
│
├── screenshots/
│   ├── home.png
│   ├── dashboard.png
│   └── prediction.png
│
└── assets/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YourUsername/IEEE-CIS-Fraud-Detection.git
```

Move into the project folder

```bash
cd IEEE-CIS-Fraud-Detection
```

Install required packages

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

# 📈 Future Improvements

The following enhancements can further improve the project:

- Real-time fraud detection
- Explainable AI using SHAP
- Automated preprocessing pipeline
- REST API integration
- Cloud deployment
- User authentication
- Live transaction monitoring
- Deep Learning-based fraud detection
- Docker containerization
- CI/CD deployment pipeline

---

# 💡 Key Learning Outcomes

Through this project, the following concepts were implemented and understood:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Feature Selection
- Machine Learning Algorithms
- Hyperparameter Tuning
- Model Evaluation
- Model Deployment
- Streamlit Application Development
- GitHub Project Management

---

# 📌 Applications

This project can be used in:

- Banking Systems
- Financial Institutions
- Online Payment Platforms
- Credit Card Companies
- E-Commerce Fraud Detection
- Digital Wallet Security
- Risk Management Systems

---

# 👨‍💻 Author

**Rakesh Nadakuditi**

**Project:** Advanced Credit Card Fraud Detection using Machine Learning

---

# ⭐ Repository Features

✔ End-to-End Machine Learning Project

✔ IEEE-CIS Fraud Detection Dataset

✔ Complete Data Preprocessing

✔ Feature Engineering

✔ Multiple Machine Learning Models

✔ Hyperparameter Tuning

✔ Interactive Streamlit Dashboard

✔ Batch CSV Prediction

✔ Download Prediction Results

✔ GitHub Ready

✔ Resume Ready

✔ Industry-Oriented Project
