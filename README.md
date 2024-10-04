# Predictive Maintenance: Leveraging Anomaly Detection to Prevent Machine Failures

## Project Overview

This project develops a predictive maintenance solution aimed at identifying machine anomalies and predicting potential breakdowns. Using a dataset of over 18,000 rows collected over several days, with binary labels indicating anomalies, we've created high-accuracy models capable of predicting machine failures.

## Data Analysis and Preprocessing

- Exploratory Data Analysis (EDA)
- Data Cleaning (handling missing values, removing duplicates)
- Outlier Detection and Removal using Local Outlier Factor (LOF)
- Feature Engineering (creating temporal features)

## Model Development

- Data Preparation (standard scaling, addressing class imbalance with SMOTE)
- Model Selection and Training
  - Random Forest
  - Gradient Boost
  - Logistic Regression
- Hyperparameter Tuning
- Model Evaluation using confusion matrices and AUC-ROC curves

## Results

- Gradient Boost and tuned Random Forest models achieved 0.99 accuracy
- Logistic Regression model achieved 0.87 accuracy

## Future Work

1. Real-time data integration
2. Advanced feature engineering
3. Ensemble methods
4. Explainable AI techniques
5. Continuous model updating
