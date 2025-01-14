# ML-Project-for-Income-prediction
This project analyzes census income data to predict whether individuals earn above or below a specified income threshold. Using machine learning techniques, we explore various algorithms to improve prediction accuracy and gain insights into income distribution factors.

## Abstract
This project predicts income levels using demographic and work-related attributes from the “Census Income” dataset. We evaluated Logistic Regression, Decision Tree, and Random Forest models, with Random Forest achieving the highest AUC score of 0.93.

## Introduction
The goal is to classify whether individuals earn more than $50K annually based on features like age, education, marital status, and hours worked. This analysis supports socio-economic research and policy-making.

## Methodology
- **Data Preprocessing:** Cleaned dataset (48,842 rows, 15 columns), encoded categorical variables, and selected features.
- **Models Used:** 
  - Logistic Regression
  - Decision Tree
  - Random Forest

## Results
Random Forest outperformed other models, demonstrating superior accuracy and reduced overfitting.

## Conclusion
Random Forest is the most effective model for income classification, emphasizing the importance of feature selection.

## Future Work
- Explore advanced models like XGBoost.
- Increase dataset diversity for better generalization.
- Optimize computational efficiency through dimensionality reduction.

