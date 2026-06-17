# Time Series Sales Forecasting

## Project Overview

This project focused on developing an end-to-end time series forecasting solution to predict monthly sales demand for Prism Johnson Limited. The objective was to leverage historical sales data to generate reliable future forecasts, enabling proactive production planning, inventory management, and demand forecasting. The solution incorporated statistical forecasting techniques, model validation, and benchmarking to ensure accuracy and robustness.

---
## Business Objectives

The project was designed to answer key business questions:

* What will the sales demand be over the next 12 months?
* How do trend and seasonality influence sales patterns?
* How can future demand fluctuations be anticipated for better planning?
* What impact did external events such as COVID-19 have on sales performance?
* Which forecasting model provides the most reliable predictions?

---

## Project Workflow
### 1. Exploratory Data Analysis (EDA)

Conducted exploratory analysis to understand historical sales patterns and identify:

* Long-term sales trends
* Seasonal demand patterns
* Data distribution and anomalies
* Impact of external business events

### 2. Time Series Decomposition

Decomposed the series into:

* Trend Component
* Seasonal Component
* Residual Component

This helped in understanding underlying demand behavior and selecting an appropriate forecasting approach.

### 3. Stationarity Analysis

Performed stationarity testing using:

* Augmented Dickey-Fuller (ADF) Test
* First-order Differencing
* Seasonal Differencing

to ensure the data met time series modeling assumptions.

### 4. Model Development

Built a SARIMAX forecasting model by:

* Identifying parameters using ACF and PACF plots
* Incorporating a COVID dummy variable as an exogenous feature
* Capturing both trend and seasonal effects

## 5. Model Validation & Benchmarking

Validated model performance using:

* Train-Test Split
* MAPE (Mean Absolute Percentage Error)
* Residual Diagnostics
* Rolling Cross-Validation

Benchmarked SARIMAX against:

* Naïve Forecasting
* Holt-Winters
* Auto-ARIMA
* Prophet

to identify the most robust forecasting approach.

### 6. Forecast Generation

Generated:

* 12-Month Sales Forecasts
* Forecast Confidence Intervals
* Future Demand Trend Projections

to support strategic planning and decision-making.

## Key Insights

* Identified recurring seasonal sales patterns and long-term growth trends.
* Quantified the impact of external disruptions such as COVID-19 on sales demand.
* Determined the most suitable forecasting model through comparative benchmarking.
* Improved visibility into future demand fluctuations.
* Enabled proactive planning through data-driven forecasting.

## Business Impact
* Supported production and inventory planning with forward-looking demand estimates.
* Improved visibility into future sales trends.
* Reduced uncertainty in demand planning decisions.
* Enabled data-driven forecasting instead of relying solely on historical observations.
* Established a scalable forecasting framework for future business applications.

## Project Files

## Project Files

📓 Jupyter Notebook: [Time Series Project - Sales Forecasting.ipynb](Time Series Project - Sales Forecasting.ipynb)

## Tools & Technologies

* Python
* Pandas
* NumPy
* Statsmodels
* Prophet
* Matplotlib
* Seaborn
* Jupyter Notebook

## Skills Demonstrated

* Time Series Forecasting
* SARIMA / SARIMAX Modeling
* Statistical Analysis
* Stationarity Testing
* Forecast Validation
* Feature Engineering
* Model Benchmarking
* Rolling Cross-Validation
* Forecast Accuracy Evaluation
* Business Analytics
* Data Visualization
* Demand Forecasting
* Python Programming
