# Online Retail Sales Analysis & Forecasting

## Project Overview
This project analyzes real-world online retail transaction data to uncover sales trends and forecast future revenue. The goal is to demonstrate practical data analysis, visualization, and machine learning skills using Python.

The project covers the full data science workflow:
- Data cleaning and feature engineering
- Exploratory data analysis (EDA)
- Time-based aggregation and visualization
- Machine learning forecasting using Linear Regression
- Model evaluation and interpretation

---

## Dataset
**Online Retail Dataset**

The dataset contains transactional data from an online retail store, including:
- Invoice numbers and dates
- Product quantities and prices
- Customer and country information

A new **Revenue** feature was created using:

---

## Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **Matplotlib** – data visualization
- **Scikit-learn** – machine learning (Linear Regression)
- **Jupyter Notebook**

---

## Methodology

### 1. Data Cleaning & Feature Engineering
- Converted invoice dates to datetime format
- Created a Revenue column
- Extracted monthly periods for time-based analysis

### 2. Data Aggregation
- Grouped transaction-level data into monthly revenue totals
- Created a numerical time index to represent the passage of time

### 3. Exploratory Data Analysis
- Visualized monthly revenue trends
- Identified seasonal patterns and fluctuations

### 4. Machine Learning Forecasting
- Split data into training and testing sets using a time-based split
- Trained a Linear Regression model to predict monthly revenue
- Generated predictions for unseen future months

### 5. Model Evaluation
- **Mean Absolute Error (MAE):** measures average prediction error
- **R² Score:** measures how much variance in revenue the model explains

---

## Key Insights
- Monthly revenue shows clear fluctuations, indicating seasonality in customer purchasing behavior
- Linear Regression captures the overall trend but does not fully model short-term volatility
- The model is suitable for baseline forecasting and trend analysis

---

## Future Improvements
- Apply advanced time-series models (ARIMA, Prophet)
- Include additional features such as customer segments or country-level analysis
- Perform hyperparameter tuning and cross-validation

---

## Portfolio Takeaway
This project demonstrates the ability to:
- Work with messy, real-world data
- Perform end-to-end data analysis
- Build and evaluate machine learning models
- Communicate insights clearly for business decision-making
