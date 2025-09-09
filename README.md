🏥 Health Insurance Premium Prediction

This project predicts health insurance premiums based on demographic, lifestyle, and medical history features.
The goal is to estimate insurance costs using regression models and deploy the prediction system with an interactive Streamlit web app.

🚀 Features

📊 Predicts health insurance premiums using multiple ML models

🧑‍💻 Interactive Streamlit frontend for real-time predictions

🔎 Exploratory Data Analysis (EDA) with visualization and feature checks

✅ Supports categorical & numerical inputs:

Age, Dependents, Income

Employment Status, Region, Marital Status

BMI Category, Smoking Status

Medical History, Insurance Plan

🛠️ Tech Stack

Python 🐍

Pandas, NumPy → Data preprocessing

Matplotlib, Seaborn → EDA & Visualization

scikit-learn → Linear Regression, Ridge, Lasso

XGBoost → Gradient Boosted Tree model

Streamlit → Web app deployment

📂 Project Structure
📁 HealthInsurancePremiumPrediction
│── app.py                  # Streamlit frontend
│── prediction_helper.py    # ML model logic 
│── requirements.txt        # Dependencies
│── README.md               # Documentation

📊 Model Development & Evaluation
1. Exploratory Data Analysis (EDA)

Visualized distributions & correlations using Matplotlib and Seaborn

Identified outliers and feature importance

Checked multicollinearity with Variance Inflation Factor (VIF)

2. Models Used

Linear Regression → Baseline

Ridge Regression (L2) → Regularized linear model

Lasso Regression (L1) → Feature selection capability

XGBoost → Gradient boosting for higher accuracy

3. Validation & Tuning

Train-Test Split for evaluation

Cross-validation to avoid overfitting

Hyperparameter tuning with GridSearchCV & RandomizedSearchCV

⚡ Streamlit Frontend

The frontend collects user details and predicts insurance premiums instantly.

Example Inputs:

Age: 32

Income: 15 Lakhs

BMI Category: Normal

Smoking Status: No Smoking

Medical History: Diabetes

Insurance Plan: Gold

👉 Predicted Premium: ₹24,300

🖼️ Screenshots
Input Form

Users enter demographic, lifestyle, and medical details.

Prediction Output

The system displays the predicted premium in real time.




