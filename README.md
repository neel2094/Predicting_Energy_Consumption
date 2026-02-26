## Predicting Energy Consumption

This project focuses on forecasting hourly electricity consumption using historical load data and machine learning techniques. The dataset was first cleaned and aligned to consistent hourly intervals, with missing values handled through interpolation and outliers treated using the IQR method. To capture temporal patterns, features such as time-based variables, cyclical encodings, lag values, and rolling statistics were engineered.

Multiple models, including Random Forest, XGBoost, and Linear Regression, were trained and evaluated. XGBoost achieved the best performance, demonstrating its effectiveness in capturing nonlinear relationships and seasonal demand patterns. The analysis revealed strong daily and weekly consumption cycles, with recent historical demand being the most influential predictor.

Overall, this project illustrates an end-to-end machine learning workflow for time-series forecasting and highlights how predictive models can support energy planning and decision-making.
