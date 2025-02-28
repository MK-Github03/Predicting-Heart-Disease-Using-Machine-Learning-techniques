# Predicting-Heart-Disease-Using-Machine-Learning


## Project Overview
Heart disease remains one of the leading causes of death globally. Early diagnosis and risk assessment are crucial for effective treatment and prevention. This project aims to develop a machine learning model to predict the presence of heart disease based on patient health metrics.

## Dataset
The dataset used in this project consists of 918 patient records with 12 attributes. It includes various clinical parameters such as age, cholesterol levels, blood pressure, and exercise response to determine a patient’s likelihood of developing heart disease.

- **Dataset Source:** [Kaggle - Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Features:**
  - **Predictor Variables:** Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Resting ECG, Max Heart Rate, Exercise-Induced Angina, Oldpeak (ST Depression), ST Slope.
  - **Target Variable:** `HeartDisease` (Binary: `1 = Heart Disease`, `0 = No Heart Disease`)

## Machine Learning Techniques
The project employs multiple machine learning techniques for heart disease prediction:

- **Ensemble Learning:** 
  - Random Forest (Feature Importance)
  - Gradient Boosting (XGBoost, AdaBoost)
- **Deep Learning:** 
  - Multi-Layer Perceptron (MLP) for complex feature relationships
- **Feature Selection:** 
  - Wrapper Methods (Recursive Feature Elimination - RFE)
  - Embedded Methods (Tree-based selection)
  - Filter Methods (Correlation, Mutual Information)
- **Benchmark Models:** 
  - Support Vector Machines (SVM)
  - Kernel Methods
  - Logistic Regression

## Model Evaluation Metrics
To assess model performance, we will use the following metrics:

- **Accuracy & F1-Score**: Evaluate predictive performance.
- **ROC-AUC Score**: Assess classification effectiveness.
- **Feature Importance Analysis**: Identify key predictors of heart disease.

## Expected Outcomes
- Development of a high-performing heart disease prediction model.
- Identification of key risk factors contributing to heart disease.
- Improved interpretability of machine learning models in healthcare applications.


