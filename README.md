☕ Coffee Sales Analysis & Forecasting (Python)

📌 Project Overview

This project focuses on analyzing coffee shop sales data using Python to identify sales trends, customer purchasing behavior, and demand patterns. The analysis supports inventory planning and short-term sales forecasting using time-series techniques.

🎯 Objectives

Perform Time Series Exploratory Data Analysis (EDA)

Analyze customer purchasing patterns

Compare cash vs card-based sales

Forecast next day / week / month sales

Derive insights to aid inventory management

🗂 Dataset Description

The dataset contains transactional sales data with the following fields:

date – Transaction date

datetime – Timestamp of purchase

cash_type – Mode of payment

card – Anonymized card identifier (used as a proxy for repeat customers)

money – Transaction amount

coffee_name – Product purchased

🔍 Exploratory Data Analysis (EDA)

Key analyses include:

Daily and monthly sales trends

Product-wise revenue contribution

Peak sales hours

Cash vs card sales comparison

Repeat purchase behavior using anonymized card data

All insights are supported with clear visualizations and business interpretations.

📈 Sales Forecasting

Implemented ARIMA as a baseline time-series forecasting model

Forecasted short-term daily sales (30 days)

Forecasts are used to support proactive inventory planning

📦 Inventory Planning Insights

Identified high-demand coffee products for priority stocking

Detected peak demand periods to optimize replenishment timing

Segmented demand behavior based on payment type

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib

Statsmodels (ARIMA)

Jupyter Notebook

📌 Key Takeaways

A small number of coffee products drive most revenue.

Card customers show higher repeat purchasing behavior.

Sales follow predictable time-based patterns.

Forecasting enables better inventory and demand planning.

👤 Author

Gourab Bain
Aspiring Data Analyst
