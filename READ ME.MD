Trader Behavior vs. Market Sentiment Analysis

Overview

This project analyzes the relationship between trader behavior (profitability, leverage, trade volume, and trade count) and overall market sentiment (Fear vs. Greed) using historical trading data and the Bitcoin Fear & Greed Index.

Project Structure

DS ANISH SINGH/
├── notebook_1.ipynb          # Main Jupyter Notebook with all steps  
├── csvfiles/                # Contains intermediate and processed CSV files  
│   └── mergeddata.csv       # Aggregated trader data merged with sentiment data  
├── outputs/                  # Contains saved charts and visualizations  
│   ├── avgpnl_by_sentiment.png  
│   ├── avgstartposition_by_sentiment.png  
│   ├── tradingvolume_over_time.png  
│   └── correlation_heatmap.png  
├── DS report.pdf              # Final analysis report with insights  
└── READ ME.md                  # Setup guide and project description  

Requirements

You will need the following installed:

Python 3.10 or above

Jupyter Notebook or JupyterLab

Required Python packages:

pip install pandas matplotlib seaborn

Setup Instructions

Clone or Download the Project

Place the datasets (historical_data.csv and fear_greed_index.csv) in the project folder.

Open Jupyter Notebook

jupyter notebook notebook_1.ipynb

Run the Notebook

The notebook will:

Load and clean the datasets

Aggregate trader data by date

Merge with sentiment data

Perform exploratory data analysis

Save CSV outputs and charts

Outputs

Processed CSVs will be in csv_files/

Visuals will be in outputs/

Notes

Ensure that the folder names csv_files and outputs exist before running cells that save files.

If missing, create them using:

import os
os.makedirs("csv_files", exist_ok=True)
os.makedirs("outputs", exist_ok=True)

The report (ds_report.pdf) summarizes the methodology, findings, and conclusions based on the analysis.

