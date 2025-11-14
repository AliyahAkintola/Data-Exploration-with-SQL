# SQL Finance Exploration: S&P 500 (1927–2020)

This project explores the historical performance of the S&P 500 Index using SQL. 
I used MySQL (via Jupyter Notebook) to analyze price movements, yearly trends, and year-over-year changes.

---

## 📊 Dataset Description
The dataset contains daily S&P 500 data from **1927 to 2020**, including:

- Date  
- Open price  
- High price  
- Low price  
- Close price  
- Adjusted close  
- Volume  

Volume was excluded from analysis due to formatting issues.

---

## 🔍 SQL Questions Explored

### ✔ 1. What is the **yearly high and low price**?
Using `MAX(high)` and `MIN(low)` grouped by year.

### ✔ 2. What is the **average closing price per year**?
Using `AVG(close)` grouped by year.

### ✔ 3. What is the **Year-over-Year (YoY) % change** in average closing price?

Formula:
