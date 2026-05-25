# Time Series Analysis using Apple Stock Price Dataset

## Internship Project - Synent Technologies

### Project Overview

This project focuses on performing **Time Series Analysis** on Apple stock price data using Python.  
The main objective of this project is to analyze historical stock market trends, identify seasonal patterns, understand price volatility, and generate short-term future forecasts using beginner-friendly data science techniques.

The project was developed as part of my **Data Science Internship at Synent Technologies**.

---

# Objectives of the Project

The primary goals of this project are:

- Analyze historical Apple stock price data
- Perform trend analysis on stock prices
- Detect seasonality patterns in the market
- Visualize stock movement using graphs
- Apply rolling statistics for volatility analysis
- Perform time series decomposition
- Build a simple forecasting model using ARIMA
- Generate meaningful business insights from the data

---

# Dataset Information

### Dataset Used:
**Apple Stock Price Dataset**

### Dataset File:
`apple_5yr_one.csv`

### Dataset Features:
The dataset contains historical Apple stock market information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

### Important Note:
The dataset contained one unnecessary first row, which was handled using:

```python
pd.read_csv("apple_5yr_one.csv", skiprows=1)