# Olist E-Commerce Analysis 🛒

## Overview
End-to-end analysis of 96,478 Brazilian e-commerce orders using Python, 
SQL (BigQuery), and data visualization.

## Business Questions Answered
- How has revenue trended over time?
- Which states generate the most revenue?
- What is the delivery performance and where does it fail?
- Which product categories drive the most revenue?

## Key Findings
- Average delivery time is 12 days with a 7.8% late rate
- Alagoas (AL) has the highest late delivery rate in Brazil
- Bed, Bath & Table is the #1 revenue category
- Revenue peaked November 2017, consistent with Black Friday

## Tools Used
- **Python** (pandas, matplotlib, seaborn) — cleaning & analysis
- **BigQuery (SQL)** — large scale querying
- **Jupyter Notebook** — reproducible analysis

## Dataset
[Brazilian E-Commerce by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — available on Kaggle

## How to Run
1. Download the dataset from the link above
2. Place all CSV files in a folder named `data/` in the same directory as `analysis.ipynb`
3. Run the notebook

## Project Structure
olist-ecommerce-analysis/

│

├── data/              # Download CSVs here (not included in repo)

├── charts/            # Saved visualizations

├── analysis.ipynb     # Main notebook with outputs

└── README.md
