# 📌 Financial Risk & Anomaly Detection in Stock Market Data

## 📖 Overview

Financial markets are highly dynamic and subject to sudden changes that can significantly impact investment decisions. Detecting abnormal behaviors and identifying high-risk periods is therefore essential for effective risk management.

This project proposes a data-driven approach to analyze stock market data, detect anomalies, and classify risk levels using statistical methods and machine learning techniques. It also includes an interactive dashboard for decision support.

---

## 🎯 Objectives

The main goals of this project are:

- Understand market behavior through time series analysis  
- Engineer meaningful financial features  
- Detect abnormal patterns (anomalies)  
- Identify high-risk periods in the market  
- Provide actionable insights for investment decisions  

---

## 📊 Dataset

The dataset consists of historical stock market data, including:

- **Date**: Time index  
- **Close**: Closing price  
- **High**: Highest price of the day  
- **Low**: Lowest price of the day  
- **Volume**: Trading volume  

The dataset was processed and enriched to extract meaningful insights.

---

## ⚙️ Methodology

### 1. Data Preprocessing

- Handling missing values (NaN cleaning)  
- Formatting date and time index  
- Ensuring data consistency and quality  

---

### 2. Feature Engineering

To better capture market dynamics, several financial indicators were created:

- **Return** → Measures daily price variation  
- **Volatility** → Captures market instability  
- **Moving Averages (MA_5, MA_10)** → Identify trends  
- **Volume Change** → Detect unusual trading activity  
- **High-Low Spread (HL_Spread)** → Measures intraday fluctuations  

These features are essential for identifying abnormal behavior.

---

### 3. Anomaly Detection

Two complementary techniques were used:

#### 🔹 Z-Score Method
- Measures how far a value deviates from the mean  
- Useful for detecting extreme events  

#### 🔹 Isolation Forest
- Unsupervised machine learning algorithm  
- Detects rare and unusual observations  
- Works well with multidimensional data  

**Output:**
- `-1` → Anomaly  
- `1` → Normal  

---

### 4. Risk Classification

Based on volatility and anomaly detection, market conditions were classified into:

- 🟢 **Low Risk** → Stable market conditions  
- 🟠 **Medium Risk** → Moderate fluctuations  
- 🔴 **High Risk** → High volatility or anomalies  

This simplifies interpretation for decision-making.

---

### 5. Data Visualization & Dashboard

A Power BI dashboard was developed to provide:

- 📈 Price evolution over time  
- 🚨 Detection of anomalies  
- 📊 Volatility and volume analysis  
- 🎯 Risk level monitoring  

The dashboard allows users to interactively explore market behavior.

---

## 📈 Results & Insights

The analysis revealed:

- Clear detection of abnormal market movements  
- Strong link between high volatility and anomalies  
- Periods of high risk associated with large price swings  
- Volume spikes often coincide with anomalies  

These insights are valuable for anticipating risky situations.

---

## 💡 Business Value

This project provides practical value for:

- 📊 **Investors** → Identify risky investment periods  
- 🏦 **Financial Analysts** → Monitor market behavior  
- 📉 **Risk Managers** → Improve risk assessment strategies  

It enables **data-driven decision-making** in financial contexts.

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy)  
- **Scikit-learn** (Isolation Forest)  
- **Matplotlib / Seaborn** (visualization)  
- **Power BI** (dashboard)  

---

## 📂 Project Structure
