# Forecasting Urban Noise Pollution in Boston Using Time Series Analysis

This project analyzes and forecasts urban noise complaint patterns in Boston using historical 311 service request data. The goal is to identify temporal and neighborhood-level noise trends, perform exploratory data analysis, and build a time series forecasting model that can help anticipate future noise complaint activity.

## Project Overview

Urban noise pollution is a major quality-of-life issue in large cities. In this project, Boston 311 noise complaint data was studied to understand how complaints vary across time, weekdays, seasons, and neighborhoods. After cleaning and transforming the data, time series modeling was performed to forecast future complaint patterns.

The project combines:
- data preprocessing
- exploratory data analysis
- feature engineering
- time series forecasting
- model comparison and interpretation

## Objectives

- Build a clean and structured dataset of Boston noise complaints
- Identify hourly, daily, weekly, and seasonal noise patterns
- Explore neighborhood-level complaint trends
- Model the complaint counts as a time series
- Forecast future noise complaint activity for planning and decision-making

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## Repository Structure

```text
forecasting-urban-noise-pollution-boston/
│
├── notebook/
│   └── PROEJCT_2_DME.ipynb
│
├── report/
│   └── Project2_Hitaxi_Dev.pdf
│
├── results/
│   ├── daily_trend_analysis.png
│   ├── weekday_weekend_pattern.png
│   └── model_forecast_comparison.png
│
├── requirements.txt
└── README.md
