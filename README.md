# End-to-End Sales Forecasting & Demand Intelligence System

## Project Overview

This project is an end-to-end Sales Forecasting and Demand Intelligence System developed using Python. It analyzes historical retail sales data, forecasts future sales, detects anomalies, segments products based on demand patterns, and provides an interactive dashboard for business decision-making.

The project was developed as part of an AI/ML Internship.

---

## Objectives

- Analyze historical sales data
- Forecast future sales using multiple models
- Detect unusual sales patterns
- Segment products based on demand
- Build an interactive dashboard using Streamlit
- Generate business insights for inventory planning

---

## Dataset

### Primary Dataset
- Superstore Sales Dataset (`train.csv`)

### Secondary Dataset
- Video Game Sales Dataset (`vgsales.csv`)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Prophet
- XGBoost
- Scikit-learn
- Streamlit

---

## Project Tasks

### Task 1 – Data Loading & Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Missing Value Analysis
- Business Insights

### Task 2 – Time Series Analysis
- Monthly Sales Trend
- Time Series Decomposition
- ADF Stationarity Test
- Differencing

### Task 3 – Sales Forecasting
- SARIMA
- Facebook Prophet
- XGBoost
- Model Comparison (MAE, RMSE, MAPE)

### Task 4 – Category & Region Forecasting
- Furniture Forecast
- Technology Forecast
- Office Supplies Forecast
- West Region Forecast
- East Region Forecast

### Task 5 – Anomaly Detection
- Isolation Forest
- Z-Score Method
- Weekly Sales Analysis

### Task 6 – Product Demand Segmentation
- K-Means Clustering
- Elbow Method
- PCA Visualization
- Stocking Strategy

### Task 7 – Streamlit Dashboard
- Sales Overview
- Forecast Explorer
- Anomaly Report
- Demand Segmentation

### Task 8 – Executive Business Report
- Business Summary
- Forecast Results
- Recommendations
- Limitations

---

## Project Structure

```
SalesForecasting_Sharanya/
│
├── analysis.ipynb
├── app.py
├── train.csv
├── vgsales.csv
├── requirements.txt
├── Task8_Executive_Business_Report.pdf
├── charts/
└── README.md
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/YourUsername/SalesForecasting_Sharanya.git
```

2. Install the required libraries

```
pip install -r requirements.txt
```

3. Run the Streamlit dashboard

```
streamlit run app.py
```

---

## Features

- Sales Forecasting
- Demand Prediction
- Time Series Analysis
- Machine Learning Models
- Anomaly Detection
- Product Segmentation
- Interactive Dashboard

---

## Future Improvements

- Include external factors such as weather and holidays
- Improve forecasting accuracy using deep learning models
- Add real-time sales monitoring
- Deploy the dashboard on a cloud platform

---

## Author

**Saranya**

B.Tech – Electrical and Electronics Engineering (EEE)

AI/ML Internship Project
