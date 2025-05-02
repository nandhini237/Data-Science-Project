Leveraging Healthcare Data for Predictive Analysis of Patient Outcomes
This MSc Data Science project explores the use of machine learning to classify healthcare test results as Normal or Abnormal using structured patient data. Two models, XGBoost and Artificial Neural Network (ANN), were implemented and compared. The project also emphasizes model interpretability using SHAP values.

Research Question
Are interpretable machine learning models capable of accurately predicting healthcare test outcomes as Normal or Abnormal based on structured patient data?

Objectives
Clean and preprocess a structured healthcare dataset

Train and evaluate XGBoost and Artificial Neural Network models

Apply hyperparameter tuning using RandomizedSearchCV and GridSearchCV

Evaluate model performance using accuracy, precision, recall, F1-score, and AUC-ROC

Use SHAP to enhance interpretability of model predictions

Dataset
Title: Healthcare Dataset: Patient Test Results

Source: Kaggle

Link: https://www.kaggle.com/datasets/prasad22/healthcare-dataset

Size: 54966 rows and 8 columns

Description: Synthetic dataset including demographic, clinical, and billing information. Fully anonymized and suitable for academic use.

Methodology
Programming Language: Python

Development Environment: Jupyter Notebook

Libraries: pandas, scikit-learn, xgboost, SHAP, matplotlib, seaborn

Preprocessing: Duplicate removal, label encoding, feature scaling

Models used: XGBoost and MLPClassifier (ANN)

Tuning methods: RandomizedSearchCV for XGBoost, GridSearchCV for ANN

Evaluation metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC

Model explanation: SHAP summary and force plots

Results
Model performance was evaluated based on several metrics. The final outcomes are summarized below.

XGBoost Model

Accuracy: 53.6 percent

AUC: 0.547

F1-Score: 0.54

ANN Model

Accuracy: 51.1 percent

AUC: 0.517

F1-Score: 0.51

Key Features Identified by SHAP

Billing Amount

Age

Blood Type

XGBoost outperformed ANN in terms of accuracy and interpretability. SHAP visualizations provided transparency and insights into model decisions, which is essential in healthcare applications.

Dataset author: Ararshi Kumar via Kaggle
