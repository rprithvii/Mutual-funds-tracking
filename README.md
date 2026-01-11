# 📈 Multi-Asset Performance Tracker
> **A Comprehensive Dashboard for 200+ Mutual Funds, Global Indices, and Equities.**

This project is a high-performance data tracking tool built to analyze and compare the growth trajectories of Indian Mutual Funds, Global ETFs, and Individual Stocks. It tracks everything from short-term daily movements to **35-year long-term CAGR**.

---

## 🔗 Live Project Link
Access the interactive dashboard here: 
**[View Live Google Sheet](https://docs.google.com/spreadsheets/d/1StYqTB1gb-7e2UygN3SCRMWfRZvfkbYaqtOBp_MDgAI/edit?gid=1001243271#gid=1001243271)**

---

## 🚀 Key Features

* **Multi-Timeframe Analysis:** Tracks performance across 1D, 1Y, 3Y, 5Y, 10Y, 20Y, and up to 35-year horizons.
* **Automated CAGR Calculations:** Advanced formulas to calculate Compound Annual Growth Rates for long-term wealth assessment.
* **Global Market Coverage:** * **India:** Nifty 50, Sensex, and specialized sectoral indices.
    * **Global:** NASDAQ-100, S&P 500, Nikkei 225 (Japan), and US Tech giants.
* **Mutual Fund Deep-Dive:** Tracking Expense Ratios, NAV, and performance for top AMC houses like Quant, Axis, HDFC, and Motilal Oswal.
* **Stock Monitoring:** Focused tracking on high-growth potential stocks (e.g., Alphalogic Techsys, NVIDIA, Microsoft).

---

## 📂 Sheet Architecture

| Sheet Name | Purpose | Data Tracked |
| :--- | :--- | :--- |
| **Shares India** | Domestic Equity Tracking | PE Ratios, Growth Categories, Small-cap Analysis |
| **Shares Global** | International Exposure | US Tech, Semiconductor ETFs, Global Indices |
| **MFs Performance** | Fund Analysis | Direct vs. Regular, Expense Ratios, CAGR Benchmarking |
| **Global Currencies** | Macro Analysis | USD/INR and JPY/INR impact on returns |

---

## 🛠 Technical Details

The project utilizes **Google Finance API** to fetch real-time data and historical pricing.

### Formula Sample (CAGR)
For calculating the 5-year growth, the project uses:
`=((Current_Price / Price_5_Years_Ago)^(1/5))-1`

---

## 💡 How to Use This Tracker

1.  **Filter by CAGR:** Use the filters on the 5Y or 10Y columns to find the most consistent wealth creators.
2.  **Expense Ratio Check:** Compare the "Exp Ratio" column against performance to see if you are paying too much for underperforming funds.
3.  **Benchmark Comparison:** Compare individual fund performance against the **Nifty 50** or **NASDAQ-100** columns to see if they are beating the market.

---

## ⚠️ Disclaimer
*This tracker is for educational and research purposes only. Investing in mutual funds and stocks involves market risks. Always consult with a certified financial advisor before making investment decisions.*

---
**Developed by [Prithvi Raj/rprithvii]** *Contributing to transparent financial data analysis.*
