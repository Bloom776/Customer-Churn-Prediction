# Telco Customer Churn Prediction

## Project Overview
**Goal**: Predict customer churn to help the business retain customers and reduce revenue loss.

**Target**: Achieve a Recall of 80% to capture as many potential churners as possible.

**Model**: XGBoost Classifier.

Customer churn is a critical metric for subscription-based businesses. This project analyzes customer data to identify key drivers of churn and builds a machine learning model to predict which customers are at risk of leaving.

[Notebook](https://github.com/Bloom776/Customer-Churn-Prediction/blob/main/notebooks/01_churn_analysis_and_modeling.ipynb)

## Results
![](https://github.com/Bloom776/Customer-Churn-Prediction/blob/main/images/Top_10_feature_importance_for%20churn_prediction.png)

- **AUC-ROC Score**: **0.82** (Strong ability to distinguish between churners and non-churners)
- **Recall (Churn Class)**: **69%** (Captures a significant portion of at-risk customers)
- **Accuracy**: 75%

## Business Impact
By identifying at-risk customers, the business can intervene with targeted retention offers.
- **Estimated ROI**: Based on the test set analysis, the model's ability to identify churners could save approximately **$30,000** in potential lost revenue (assuming a successful retention campaign).
- **Strategy**: Focus retention efforts on customers identified as "High Risk" by the model.

## Key Insights
The top drivers of churn identified by the model are:
1. **Contract Type**: Customers with **Month-to-month contracts** are the highest risk factor.
2. **Internet Service**: Users with **Fiber optic** service have higher churn rates.
3. **Payment Method**: **Electronic check** payments are associated with higher churn.

## Tech Stack
- **Python**
- **Pandas** & **NumPy** (Data Manipulation)
- **Scikit-Learn** (Preprocessing & Evaluation)
- **XGBoost** (Machine Learning Model)
- **Matplotlib** & **Seaborn** (Visualization)
