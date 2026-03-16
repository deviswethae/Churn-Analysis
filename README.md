## 📊 Customer Churn Analysis & Prediction

An end-to-end Customer Churn Analysis and Prediction System built using Machine Learning, Explainable AI (SHAP), and Power BI Dashboarding.

This project predicts whether a customer will churn and provides business-driven insights to improve retention strategies.

## 🚀 Project Overview

Customer churn is a major problem for subscription-based businesses.

This project:

📌 Analyzes customer behavior

🤖 Builds ML models to predict churn

📈 Evaluates model performance

🧠 Uses SHAP for explainability

📊 Creates interactive Power BI dashboard

💡 Suggests retention strategies

## 🛠️ Tech Stack
👨‍💻 Programming & ML

🐍 Python

📦 Pandas, NumPy

📊 Matplotlib, Seaborn

🤖 Scikit-learn

🌲 XGBoost / Random Forest

🧠 SHAP (Explainable AI)

📊 Visualization

## Power BI

📂 Project Structure
customer-churn-analysis/
│
├── data/
│   ├── churn_dataset.csv
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── shap_analysis.ipynb
│
├── models/
│   ├── final_model.pkl
│
├── powerbi_dashboard/
│   ├── churn_dashboard.pbix
│
├── requirements.txt
└── README.md

## 📌 Problem Statement

Predict whether a customer will churn based on:

Demographics

Account Information

Service Usage

Billing Details

Contract Type

## 🔍 Workflow

# 1️⃣ Data Preprocessing

Handled missing values

Removed duplicates

Label encoding / One-hot encoding

Feature scaling

Train-test split

# 2️⃣ Exploratory Data Analysis (EDA)

Churn distribution

Contract type vs churn

Tenure vs churn

Monthly charges analysis

Correlation heatmap

# 3️⃣ Model Training

Models tested:

Logistic Regression

Decision Tree

Random Forest

XGBoost

# ✅ Final Model Selected:

XGBoost (Best Performance)

📊 Final Model Performance

🎯 Accuracy: 96%

📈 ROC-AUC Score: 0.9910

🔎 High Precision & Recall

The model effectively distinguishes churners from non-churners.




























🧠 Explainable AI (SHAP Analysis)

To understand why customers churn:

SHAP Summary Plot

SHAP Feature Importance

Individual Prediction Explanation

🔥 Top Features Influencing Churn:

Contract Type

Tenure

Monthly Charges

Payment Method

Internet Service Type

📈 Power BI Dashboard

Interactive dashboard includes:

📊 Churn Rate Overview

👥 Customer Segmentation

📅 Tenure Distribution

💰 Revenue Impact

📌 High-Risk Customers

Business users can filter by:

Contract type

Gender

Payment method

Internet service

💡 Business Insights

Month-to-month customers have highest churn risk

Customers with high monthly charges are more likely to churn

Short tenure customers are highly unstable

Automatic payment users churn less

🎯 Retention Strategies Suggested

Offer discounts for long-term contracts

Promote auto-payment setup

Early engagement for new customers

Personalized offers for high monthly charge users

📦 Installation
Step 1: Clone Repository
git clone https://github.com/deviswethae/Churn-Analysis.git
cd customer-churn-analysis
Step 2: Install Dependencies
pip install -r requirements.txt

Or manually:

pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
Step 3: Run Notebook

Open Jupyter Notebook:

jupyter notebook

Run:

data_preprocessing.ipynb

model_training.ipynb

shap_analysis.ipynb

📊 Model Evaluation Metrics Used

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC Curve

ROC-AUC Score

🔮 Future Enhancements

Deploy model using Streamlit

Real-time churn prediction API

Automated retraining pipeline

Integration with CRM system

Deep learning model comparison

👩‍💻 Author

Devi Swetha E
MSc Computer Science
Software Developer & Data Analyst
📍 Coimbatore, Tamil Nadu, India

