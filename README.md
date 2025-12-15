# Quarterly Revenue Forecasting Using ARIMA

![Revenue prediction for 2026](quarterly_revenue_forecast.png)

## Project Overview
This project forecasts quarterly revenue for a fintech company using time-series analysis and ARIMA modeling. The goal is to provide management with data-driven revenue expectations for the upcoming year.

## Business Objective
- Predict next year’s quarterly revenue
- Identify trend and seasonality
- Support budgeting and strategic planning

## Methodology
1. Data aggregation at quarterly level
2. Time-series exploratory data analysis (EDA)
3. Stationarity and autocorrelation testing
4. Seasonal ARIMA (SARIMA) modeling
5. Forecasting with confidence intervals

## Key Insights
- Revenue shows consistent long-term growth
- Strong quarterly seasonality exists
- Forecast indicates continued growth with manageable volatility

## Tools Used
- Python
- Pandas
- Matplotlib & Seaborn
- Statsmodels
- Jupyter Notebook

##  Project Structure
├── arima_data.csv
├── quarterly_revenue_forecast.ipynb
└── README.md



## Challenges
- Quarterly date is too small so I changed to Monthly-level forecasting to give fiures that I can communicate to management

![Revenue prediction for 2026](Month-over-Month Revenue Growth.png)

![Revenue prediction for 2026](monthly_revenue_forecast.png)

