# Kaggle-Project-Insurance-Premium-Prediction-Using-Tabular-Machine-Learning-Python-

***📊 Project Overview***

- Cleaned and prepared a mixed-type insurance dataset

- Performed EDA with strong visual insights

- Engineered domain-based features for improved prediction power

- Built and compared multiple models:

- Linear Regression

- Random Forest

- XGBoost Regressor (best)

- Achieved low RMSE and RMSLE, with XGBoost showing the strongest generalization

- Identified key drivers of insurance premium levels


***📊 Dataset***

Target variable: Premium Amount

Features include:
Age, Annual Income, Occupation, Health Score, Vehicle Age, Number of Dependents, etc.

Key Insights

1. Premiums are strongly influenced by Age, Health Score, Annual Income, and Vehicle Age

2. XGBoost handles non-linear patterns and mixed data types especially well

3. Feature engineering significantly improved model stability and reduced overfitting


***Conclusion***
The overfitting analysis indicates that the XGBoost model generalizes well. The difference between training RMSE and validation RMSE is negligible, suggesting that the model is not memorizing the training data and is able to capture the underlying patterns effectively. Interestingly, the training error is slightly higher than the validation error, which can occur when the learning rate is low, the training data contains more noise than the validation subset, and/or regularization parameters (e.g., min_child_weight, subsample, colsample_bytree) encourage smoother decision trees and reduce variance.


***🔍Future Improvements***

1. Add SHAP-value interpretability

2. Implement automated ML pipelines

3. Hyperparameter Optimization
   
4. Try GradientBoosting / LightGBM

5. Deploy model via FastAPI or Streamlit dashboard

