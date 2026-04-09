# Retail Sales Anomaly Detection Using Unsupervised Learning

## Overview
This project applies unsupervised machine learning techniques to detect unusual transaction patterns in retail pizza sales data. Using more than 48,000 transaction records, the analysis identifies abnormal purchasing behavior, high-value orders, and deviations from normal sales activity.

The project combines data cleaning, exploratory data analysis, feature engineering, preprocessing, and anomaly detection modeling to generate business-oriented insights from transaction-level data.

## Objective
The main goal of this project is to detect anomalous retail transactions and understand how unusual sales behavior differs from normal transaction patterns.

## Dataset
The dataset contains transaction-level pizza sales data, including:

- order ID
- pizza name
- quantity
- unit price
- total price
- pizza size
- pizza category
- order date
- order time

After cleaning, the final dataset used in the analysis contained over 48,000 observations.

## Methods Used
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Standardization and one-hot encoding
- Isolation Forest
- Local Outlier Factor

## Key Findings
- Isolation Forest identified approximately 2% of transactions as anomalous.
- Anomalous transactions were associated with higher quantities and significantly higher total prices.
- The **Classic** category showed the highest anomaly count and the highest anomaly rate.
- Anomalies were strongly concentrated around **12:00 and 13:00**, suggesting unusual purchase behavior during peak lunch hours.
- Isolation Forest produced the most interpretable business results, mainly identifying high-value and less frequent transactions.

## Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- openpyxl
- kagglehub

## Repository Structure
```bash
.
├── 01_retail_sales_anomaly_detection.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
