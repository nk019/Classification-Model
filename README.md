# Classification-Model
🧠 Notebook Goal
End-to-End Credit Card Fraud Detection

EDA → Feature Engineering
Imbalanced data handling
Train multiple ML models
Proper evaluation & insights
📑 Table of Contents
Introduction
Dataset Overview
Import Libraries
Data Loading
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Handling Imbalanced Data
Data Preprocessing
Model Building
Model Evaluation
Feature Importance
Conclusion & Future Work
🟢 1. Introduction (Notebook Text)
Credit card fraud is a major challenge in the financial sector. This notebook presents an end-to-end machine learning approach to detect fraudulent transactions using a synthetic dataset of 10,000 credit card records.

The goal is to explore transaction patterns, handle class imbalance, and compare multiple classification models using appropriate evaluation metrics.

📊 2. Dataset Overview
Rows: 10,000
Features: 10
Target: is_fraud
Imbalanced distribution (~5%)
📈 3. EDA (High-Quality Visual Ideas)
Use for-loops to keep code clean 👇

Key Plots
Fraud vs Non-Fraud count
Amount distribution (hist + KDE)
Fraud by transaction hour
Boxplot: Amount vs Fraud
Correlation heatmap
⚙️ 4. Feature Engineering
Amount to risk ratio
Night transaction flag
High velocity flag
⚖️ 5. Handle Imbalanced Data
Explain clearly why accuracy is misleading.

Options:

Class weight
SMOTE
🤖 6. Models to Train (5–8 is perfect)
Logistic Regression
Decision Tree
Random Forest
XGBoost
LightGBM
CatBoost
📏 7. Evaluation Metrics (Very Important)
Use:

Precision
Recall
F1-Score
ROC-AUC
Confusion Matrix
📌 8. Feature Importance
(Random Forest / XGBoost)

🧾 9. Conclusion (Notebook Text)
This notebook demonstrated how machine learning models can effectively identify fraudulent credit card transactions despite class imbalance. Tree-based models performed particularly well, achieving high recall while minimizing false negatives.
