#⚡ Energy Consumption Forecasting
📌 Overview

This project predicts hourly electricity consumption using historical load data and machine learning models. The workflow includes data preprocessing, feature engineering, model training, evaluation, and insights for energy demand planning.

🎯 Objective

Analyze consumption patterns

Forecast hourly electricity demand

Compare multiple ML models

🛠️ Approach

Cleaned and aligned hourly time-series data

Created temporal, lag, and rolling features

Trained Random Forest, XGBoost, and Linear Regression

Tuned models using GridSearchCV

📊 Results
Model	MAE	RMSE	R²
Random Forest	70.31	96.70	0.9967
XGBoost	62.47	84.83	0.9974
Linear Regression	141.54	182.95	0.9881

Best Model: XGBoost

🔍 Key Insights

Strong daily and weekly demand patterns

Lag features are the most important predictors

Tree-based models perform best

📦 Tech Stack

Python • Pandas • Scikit-learn • XGBoost • Matplotlib

📌 Conclusion

Machine learning models, especially XGBoost, can accurately forecast electricity demand and support energy planning decisions.
