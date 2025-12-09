# Kaggle-Project-Insurance-Premium-Prediction-Using-Tabular-Machine-Learning-Python-

Project Highlights

Cleaned and prepared a mixed-type insurance dataset

Performed EDA with strong visual insights

Engineered domain-based features for improved prediction power

Built and compared multiple models:

Linear Regression

Random Forest

XGBoost Regressor (best)

Achieved low RMSE and RMSLE, with XGBoost showing the strongest generalization

Identified key drivers of insurance premium levels


📊 Dataset

Target variable: Premium Amount

Features include:
Age, Annual Income, Occupation, Health Score, Vehicle Age, Number of Dependents, etc.

Key Insights

Premiums are strongly influenced by Age, Health Score, Annual Income, and Vehicle Age

XGBoost handles non-linear patterns and mixed data types especially well

Feature engineering significantly improved model stability and reduced overfitting


Future Improvements

Add SHAP-value interpretability

Implement automated ML pipelines

Try GradientBoosting / LightGBM

Deploy model via FastAPI or Streamlit dashboard

