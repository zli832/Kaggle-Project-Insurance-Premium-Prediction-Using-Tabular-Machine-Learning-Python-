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


***Future Improvements***

1. Add SHAP-value interpretability

2. Implement automated ML pipelines

3. Try GradientBoosting / LightGBM

4. Deploy model via FastAPI or Streamlit dashboard

