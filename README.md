# 📈 Stock Market Data Analysis

---

<p align="center">

![Python](https://img.shields.io/badge/PYTHON-3.12-blue)
![Pandas](https://img.shields.io/badge/PANDAS-DATA_ANALYSIS-black)
![NumPy](https://img.shields.io/badge/NUMPY-COMPUTING-blue)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-VISUALIZATION-orange)
![Seaborn](https://img.shields.io/badge/SEABORN-VISUALIZATION-green)
![Jupyter](https://img.shields.io/badge/JUPYTER-NOTEBOOK-orange)
![EDA](https://img.shields.io/badge/EDA-EXPLORATORY_ANALYSIS-purple)

</p>

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Nasdaq securities dataset to understand the characteristics of listed securities, market categories, ETFs, listing exchanges, and financial status.

The analysis focuses on identifying patterns between:

- 📊 Market categories
- 💰 Financial status
- 📈 ETFs
- 🏦 Listing exchanges
- 🔤 Security symbols
- 🏢 Security names

---

## 🎯 Objectives

- 🔍 Understand the structure of the stock market dataset
- 🧹 Identify and handle missing values
- 📊 Analyze market categories
- 📈 Explore ETF distributions
- 🏦 Compare listing exchanges
- 💰 Analyze financial status
- 🔎 Study relationships between ETFs and market categories
- 📉 Identify categories associated with financially distressed securities

---

## 📊 Dataset

The dataset contains **8,049 securities** and **12 original columns**.

### 📋 Features

| Feature | Description |
|---|---|
| `Nasdaq Traded` | Indicates whether the security is Nasdaq traded |
| `Symbol` | Unique trading symbol |
| `Security Name` | Full name of the security |
| `Listing Exchange` | Exchange where the security is listed |
| `Market Category` | Market classification |
| `ETF` | Indicates whether the security is an ETF |
| `Round Lot Size` | Standard round lot size |
| `Test Issue` | Indicates whether the security is a test issue |
| `Financial Status` | Financial standing/status |
| `CQS Symbol` | CQS trading symbol |
| `NASDAQ Symbol` | Nasdaq symbol |
| `NextShares` | Indicates whether the security is a NextShares product |

---

## 🛠️ Tools & Technologies

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 📓 Jupyter Notebook
- 🔍 Exploratory Data Analysis

---

## 💡 Key Findings
📊 The dataset contains 8,049 securities.
🔤 Every security has a unique Symbol.
🏢 Security names are not always unique because different securities can share related names.
📈 ETFs are generally separate from traditional company market categories.
💰 Most securities have a Normal (N) financial status.
⚠️ Financially distressed statuses such as D, E, and H occur more frequently in the S market category.
📊 ETFs are overwhelmingly associated with normal financial status.
🏦 Different listing exchanges contain different types of securities.

---

## 📝 Conclusion

The Stock Market Data Analysis project demonstrates how Exploratory Data Analysis can be used to understand the structure and characteristics of securities listed in the Nasdaq dataset.

The analysis shows that ETFs behave differently from traditional company securities, particularly in terms of market-category classification and financial-status reporting. Most securities are classified as financially normal, while financially distressed statuses appear more frequently within the S market category.
