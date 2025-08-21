🧠 AI-Powered Sales Forecasting Dashboard

This project builds an AI-powered dashboard for predicting and visualizing sales using Machine Learning (XGBoost). The model learns patterns from historical sales data, applies feature engineering (lags, rolling averages, date-based features), and generates forecasts to help businesses make data-driven decisions.

🚀 Features

Loads and processes sales data from CSV (dataset.csv)

Aggregates daily sales and engineers predictive features

Trains an XGBoost regression model for sales forecasting

Generates multiple visualizations:

Actual vs. Predicted Sales (line chart)

Scatter plot (Actual vs. Predicted)

Residual plot

Feature importance ranking

Saves predictions to sales_forecast_predictions.csv

Calculates evaluation metrics:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R² Score

Accuracy within 10% tolerance

📊 Example Outputs

Actual vs. Predicted Sales

Scatter Plot: Actual vs. Predicted

Residual Plot

Feature Importances (XGBoost)

📈 Model Performance

The model evaluates accuracy using multiple metrics:

MSE – Mean Squared Error

MAE – Mean Absolute Error

R² Score – Goodness of fit

Accuracy within 10% tolerance

Screenshots of Results:
<img width="854" height="630" alt="ml03" src="https://github.com/user-attachments/assets/296734bb-30ad-42ef-8c55-043ff92630c3" />
<img width="1246" height="624" alt="ml01" src="https://github.com/user-attachments/assets/1f0e7487-9b68-4dab-a2fe-d81d7c01bdb3" />
<img width="863" height="861" alt="ml02" src="https://github.com/user-attachments/assets/78793205-d795-4a52-8421-add7f3ea541b" />



🔮 Future Improvements

Add support for seasonal decomposition (SARIMA/Prophet)

Deploy as a web dashboard (e.g., Flask/Streamlit)

Automate data pipeline for live sales updates

Enhance visualization with interactive charts

🙌 Acknowledgment

This project was built as part of my Machine Learning Internship at Future Interns.
