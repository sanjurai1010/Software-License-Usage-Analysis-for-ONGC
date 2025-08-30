# Software-License-Usage-Analysis-for-ONGC
Analyzing ONGC software license logs to generate daily &amp; monthly usage insights with min, max, and average trends.

📖 Overview

This project focuses on analyzing software license usage logs for ONGC. The goal is to understand how different software features are used over time and generate meaningful insights through daily, monthly, and overall usage reports.

The analysis helps ONGC optimize license allocation, monitor peak usage, and improve cost efficiency.

📊 Dataset

Source: ONGC license usage logs

Type: Time-series log data (Date, Feature, Usage counts)

Attributes Used:

Feature (software feature name)

Date

Min Usage

Max Usage

Avg Usage

🛠️ Technologies Used

Programming Language: Python

Libraries:

Pandas → data preprocessing & aggregation

Matplotlib → visualization of usage trends

NumPy → numerical operations

Environment: Jupyter Notebook

⚙️ Project Workflow

Data Cleaning & Preprocessing

Parsed raw ONGC log files.

Extracted relevant fields (Feature, Date, Min, Max, Avg).

Daily Usage Analysis

Tracked daily feature-wise license usage.

Monthly Usage Analysis

Aggregated license usage by month for trend detection.

Visualization

Line plots and bar graphs for usage patterns.

Comparative feature usage across time.

Reporting

Exported summary reports (CSV/Excel).

📈 Results & Insights

Identified peak usage hours and features with highest demand.

Observed monthly growth/decline trends in software usage.

Generated automated reports for ONGC management.

🚀 Future Work

Automate reporting pipeline using ETL workflows.

Add interactive dashboards (Power BI / Streamlit).

Predict future license demand using time-series forecasting (ARIMA/LSTM).
