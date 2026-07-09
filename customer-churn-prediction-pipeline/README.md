```markdown
# Customer Churn Prediction Pipeline

A reusable ML pipeline predicting customer churn using scikit-learn's Pipeline API, 
with hyperparameter tuning via GridSearchCV.

## Results
- **Model:** Logistic Regression (chosen for higher recall on churners)
- **Test Recall (Yes/Churn):** 79%
- **Test Precision (Yes/Churn):** 51%
- **Test Accuracy:** 74%

## Tech Stack
scikit-learn (Pipeline, GridSearchCV), joblib

## Dataset
[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) — Kaggle

## Files
- `task2phase2.ipynb` — full notebook
- `churn_prediction_pipeline.joblib` — exported trained pipeline
```
