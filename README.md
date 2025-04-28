# DTSA_5509_Final_Project
 
# Heart Disease Prediction Using Supervised Learning

This project applies supervised machine learning techniques to predict the presence of heart disease based on clinical and lifestyle features. The task is a binary classification problem where the target variable indicates the presence (`1`) or absence (`0`) of heart disease.

## Project Overview
- **Learning Type:** Supervised Learning
- **Task Type:** Binary Classification
- **Goal:** Predict heart disease early to support timely medical intervention.

## Methods
- Exploratory Data Analysis (EDA) was conducted to understand feature relationships and class balance.
- Features were scaled using `StandardScaler`.
- Four models were trained and evaluated:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - Support Vector Classifier (SVC)

## Results
- The Support Vector Classifier (SVC) achieved the best performance with an accuracy of **87.5%** and an ROC AUC score of **0.94**.
- Final evaluation included confusion matrix analysis and ROC curve plotting.

## Files
- `heart_disease_prediction.ipynb` — Full project notebook.
- `heart_disease_prediction.html` — Rendered HTML version of the notebook.

## Future Work
- Explore advanced feature engineering and dataset expansion.
- Investigate handling class imbalance using techniques like SMOTE.
- Perform extended hyperparameter tuning across multiple models.

---
