# ATM Fraud Detection System

## Overview
This project is a **Python-based ATM Fraud Detection System** designed to identify potentially fraudulent transactions in banking data. It combines **data analysis, machine learning, and visualization techniques** to detect anomalies and risky transactions.

The system performs:
- Security checks on transactions (high amounts, rapid transactions, odd hours, suspicious logins, low or negative balances)
- Fraud scoring based on multiple risk factors
- Exploratory Data Analysis (EDA) with visualizations of transaction patterns
- Geolocation mapping of transaction locations
- Anomaly detection using **KMeans**, **DBSCAN**, **Hierarchical Clustering**, and **Isolation Forest**

---

## Features
- Detects high-risk transactions based on multiple flags
- Calculates a **Fraud Score** for each transaction
- Labels transactions as **Likely Fraud** based on threshold
- Visualizes transaction patterns:
  - Transaction amounts, frequency, and type  
  - Customer demographics and behavior  
  - Merchant activity  
  - Geolocation of transactions  
- Performs clustering and anomaly detection to find suspicious patterns
- Generates interactive Folium maps of transaction locations

---

## Dataset
The project uses a CSV file (`bank_transactions_data_2.csv`) containing transaction records with columns such as:

- TransactionID  
- CustomerID / UserID / UserName  
- TransactionAmount  
- TransactionDate  
- TransactionType  
- AccountBalance  
- LoginAttempts  
- DeviceID / IP Address  
- MerchantID  
- Location  
- CustomerAge / CustomerOccupation  
- PreviousTransactionDate  

> **Note:** Ensure your dataset contains these columns for full functionality. Missing columns may skip specific checks.

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/username/ATM-Fraud-Detection.git
