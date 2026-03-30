🛒 Online Retail Data Analysis — Python & EDA

A comprehensive exploratory data analysis (EDA) and business intelligence project using Python. This repository transforms raw transactional data into actionable insights regarding customer behavior, revenue trends, and geographic performance.
📊 Project Overview

In the competitive world of e-commerce, understanding when, where, and how customers spend is vital. This project analyzes a classic online retail dataset to identify high-value markets, peak shopping hours, and revenue growth patterns.
📁 Repository Structure

Data-analysis-on-retail-data-with-Python/
│
├── online_retail_data.csv             # Raw transactional dataset
├── retail_data_analysis.ipynb         # Main Jupyter Notebook with Python code
├── README.md                          # Project documentation
│
└── visualizations/                    # Exported insights
    ├── Monthlyrevenue.png             # Revenue growth over time
    ├── countrywiserevenue.png         # Global sales distribution
    ├── hourlytrend.png                # Peak transaction hours
    └── Distribution_of_Values.png     # Log-scaled transaction analysis

🔬 Dataset Analysis

The dataset contains transactions occurring between 2010 and 2011 for a UK-based non-store online retail business.
Feature	Description
InvoiceNo	Unique identifier for each transaction
StockCode	Product item code
Description	Product name
Quantity	Quantities of each product per transaction
InvoiceDate	Day and time when each transaction was generated
UnitPrice	Product price per unit
CustomerID	Unique identifier for each customer
Country	Name of the country where each customer resides
⚙️ Workflow & Key Insights
1. Data Cleaning & Preprocessing

    Handled missing CustomerID values.

    Filtered out cancelled orders (negative quantities).

    Created a TotalRevenue column (Quantity×UnitPrice).

    Parsed InvoiceDate into Hour, Day, and Month features.

2. Exploratory Data Analysis (EDA)
A. Temporal Trends

We identified that revenue peaks during the final quarter of the year, likely due to holiday shopping. We also mapped the Hourly Trend to find the "Golden Hours" for marketing.

    Insight: Peak transactions occur between 10:00 AM and 3:00 PM.

B. Geographic Distribution

While the UK remains the primary market, significant revenue streams were identified in Netherlands, EIRE, and Germany.
C. Transaction Value Distribution

Using a Log Scale, we normalized the transaction values to better understand the spending habits of the average customer versus "whales" (high-spenders).
📈 Visualizations
Monthly Revenue Trend	Country-wise Revenue
	
Tracking growth month-over-month.	Identifying top-performing global markets.
Hourly Shopping Patterns	Value Distribution
	
Optimizing ad spend by time of day.	Analyzing transaction density.
🛠️ Built With

    Python 3.x

    Pandas — Data manipulation and cleaning

    Matplotlib / Seaborn — Data visualization

    NumPy — Numerical operations

🚀 How to Run

    Clone the repository:
    Bash

    git clone https://github.com/dipanburja/Data-analysis-on-retail-data-with-Python.git

    Install dependencies:
    Bash

    pip install pandas matplotlib seaborn

    Run the analysis:
    Open retail_data_analysis.ipynb in Jupyter Notebook or VS Code and run all cells.

👤 Author

Dipan Burja

    Data Analysis Enthusiast

    Built: March 2026
