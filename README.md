# Customer Loyalty and Revenue Concentration Analysis  
**Purchase Frequency, Repeat Behavior & Commission Insights**

## Overview

This project presents a comprehensive exploratory analysis of **1,367 unique customers** and their purchase behavior, with a strong focus on **purchase frequency**, **repeat vs one-time segmentation**, and **commission revenue concentration**.

The analysis uncovers a classic power-law distribution: while the majority of customers are one-time buyers, a small core of highly engaged repeat customers drives the vast majority of commission revenue.

Key themes explored include:
- Customer frequency distribution and long-tail behavior
- Repeat vs One-time buyer contribution to revenue
- Pareto (80/20) analysis and revenue concentration
- Monetary aggregates and commission efficiency
- Strategic insights for retention, conversion, and growth

**Note**: All customer account numbers are pseudonymous to protect privacy. No raw transactional data is generated or stored in this repository.

## Project Structure
customer-commission-analysis/
├── README.md                     # This file
├── Customer_Commission_Analysis.ipynb   # Main Jupyter notebook (full analysis)
├── requirements.txt              # Python dependencies
└── data/                         # (Not included - pseudonymous data only)
text## Requirements

- Python 3.9+
- Jupyter Notebook / JupyterLab
- Key Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn (optional visualizations)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/customer-commission-analysis.git
   cd customer-commission-analysis

Install dependencies:Bashpip install -r requirements.txt
Launch Jupyter Notebook:Bashjupyter notebook

Dataset

Records: 1,367 unique customers
Key Variables:
Account Number (pseudonymized)
Frequency (number of purchases)
Total Amount
Total Commission
Average Amount & Commission per Transaction

Nature: Aggregated transactional data (no individual raw transactions included)

Key Results

One-time Buyers: 782 customers (57.2%) → Contribute only 5.1% of total commission
Repeat Buyers: 585 customers (42.8%) → Generate 94.9% of total commission
Revenue Concentration: Top 13.4% of customers (183 accounts) generate 80%+ of total commission
Top 10% of customers (136 accounts) drive 73.6% of commission revenue
Ultra-High-Value Segment: 22 customers (>300 commission) average 127.6 transactions each and contribute 26.6% of total commission
Frequency Insight: High-commission customers show dramatically higher average purchase frequency (up to 140+ transactions)

Running the Analysis

Open Customer_Commission_Analysis.ipynb in Jupyter
Run cells sequentially
Follow the structured sections:
Data Loading & Preparation
Frequency Distribution Analysis
Monetary & Commission Aggregates
Pareto & Concentration Analysis
Repeat vs One-time Segmentation
Visualizations & Business Insights


Strategic Takeaways
This analysis clearly demonstrates that customer loyalty and repeat purchase frequency are the primary drivers of commission revenue.
The business exhibits strong Pareto dynamics — a small, highly engaged customer segment accounts for the majority of value.
Recommended Focus Areas:

Protecting and nurturing the top 183 high-value customers
Converting one-time buyers into repeat customers
Increasing purchase frequency among mid-tier customers
Reducing revenue concentration risk through targeted retention strategies

Next Steps & Extensions

Full RFM (Recency, Frequency, Monetary) scoring
Customer lifetime value (CLV) modeling
Cohort analysis and retention curves
Predictive modeling for repeat purchase probability
Dashboard development (Streamlit / Power BI)

Technologies Used

Python
pandas & NumPy
Matplotlib & Seaborn
Jupyter Notebook

Prepared as part of a professional customer analytics project
Focus: Retention Strategy • Revenue Concentration • Loyalty Insights
