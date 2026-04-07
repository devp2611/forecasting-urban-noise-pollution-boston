# Forecasting Urban Noise Pollution in Boston Using Time Series Analysis

This project analyzes and forecasts urban noise complaint patterns in Boston using historical 311 service request data. The goal is to identify temporal and neighborhood-level noise trends, perform exploratory data analysis, and build a time series forecasting model that can help anticipate future noise complaint activity.

---

## Project Overview

Urban noise pollution is a major quality-of-life issue in large cities. In this project, Boston 311 noise complaint data was studied to understand how complaints vary across time, weekdays, seasons, and neighborhoods. After cleaning and transforming the data, time series modeling was performed to forecast future complaint patterns.

---

The project combines:
- data preprocessing
- exploratory data analysis
- feature engineering
- time series forecasting
- model comparison and interpretation

---

## Objectives

- Build a clean and structured dataset of Boston noise complaints
- Identify hourly, daily, weekly, and seasonal noise patterns
- Explore neighborhood-level complaint trends
- Model the complaint counts as a time series
- Forecast future noise complaint activity for planning and decision-making

---

## Portfolio Value

This project demonstrates:

- Real-world data analysis using city datasets  
- Strong understanding of time series modeling  
- Ability to extract insights from complex data  
- Practical forecasting implementation  
- Clean project structuring and documentation

---

## Dataset Note

The project uses Boston 311 noise complaint data collected over multiple years.

Due to file size limitations, the merged output dataset used in the modeling stage is **not stored in this GitHub repository**. The large merged dataset has been uploaded separately to Google Drive.

**Merged Output Dataset (Google Drive):**(https://drive.google.com/file/d/1takOJp3ha_M8LT5M6wK0DCIrxn1uBU5T/view?usp=sharing)

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

---

## Data Preprocessing

- Converted timestamps into proper datetime format  
- Removed missing or invalid records  
- Sorted dataset chronologically  
- Filtered noise-related complaints using keywords  
- Extracted time-based features:
  - Hour of day  
  - Day of week  
  - Month  
  - Season  
- Aggregated complaints into daily counts  
- Created a continuous time series dataset  

---

## Exploratory Data Analysis

The analysis reveals strong patterns in urban noise behavior:

- Daily complaint trends show clear fluctuations across time  
- Warmer months have significantly higher complaint volumes  
- Late-night hours (9 PM – 2 AM) show peak activity  
- Weekends consistently have more complaints than weekdays  
- Certain neighborhoods (Allston, Fenway, Back Bay) show higher noise levels  

---

## Time Series Modeling

- Chronological train-test split (last 90 days as test set)  
- Model used: **SARIMA (Seasonal ARIMA)**  
- Configuration: SARIMA(1,1,1)(1,1,1,7)  
- Captures both trend and weekly seasonality  

---

## Model Evaluation

The model performance was evaluated using:

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- MAPE (Mean Absolute Percentage Error)  

The model successfully captures:
- Weekly seasonal patterns  
- Long-term trends  
- Short-term fluctuations  
 

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

```
---

## Key Findings

- Noise complaints peak during summer months  
- Late-night hours show the highest activity  
- Weekends have more complaints than weekdays  
- High-density and nightlife-heavy areas show consistent spikes  
- Noise behavior is structured and predictable over time  

---

## Forecast Insights

- Future complaint patterns follow strong seasonal trends  
- Weekly cycles remain consistent  
- Forecasting helps identify high-risk noise periods  
- Useful for urban planning and enforcement strategies  

---
