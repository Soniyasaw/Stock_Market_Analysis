# Stock Market Analysis and Visualization (Capstone Project)

## 📊 Project Overview
This project focuses on **analyzing and visualizing stock market trends** for top Indian companies across **five key sectors**: Automobile, Banking, IT, Pharma, and FMCG. The goal is to help investors understand **price movement, volatility, trading volume**, and the **impact of market events** using clean data and interactive dashboards.

---

## 🧩 Technologies Used
- **SQL** – For data extraction and querying
- **Python (EDA)** – For data cleaning, formatting, and preprocessing
- **Power BI** – For dashboard creation and data visualization

---

## 🗂️ Dataset Information
- **Source**: NSE (National Stock Exchange) [Imported into SQL]
- **Time Period**: April 2018 – March 2024
- **Sectors Covered**:
  - **Automobile**: Tata Motors, Maruti Suzuki
  - **Banking**: SBI, HDFC
  - **IT**: TCS, Infosys
  - **Pharma**: Sun Pharma, Dr. Reddy’s
  - **FMCG**: HUL, ITC

---

## 🧹 Data Cleaning & EDA (Exploratory Data Analysis)
Performed using Python:
- Removed commas from numeric columns (e.g., `1,20,111` → `120111`)
- Handled missing values using mean/median
- Converted date columns to datetime format
- Standardized column names
- Calculated KPIs:
  - Average Daily Return
  - Sum of High & Low
  - Total Volume (in billions)

---

## 📈 Power BI Dashboards
Created 11 dashboards:
- **10 Individual Company Dashboards** (1 per company)
- **1 Comparison Dashboard** (e.g., SBI vs. HDFC)

### Charts Included (varies by company):
- Line Charts (Price trends over time)
- Column Charts (Monthly averages, 52W high/low)
- Pie/Doughnut Charts (High-Low or Open-Close distribution)
- Bar Charts (Volume trends)
- Area Charts / Stacked Column Charts (Volume + 52W highs/lows)
- Box Plots (Price distribution and outliers)

---

## 📌 Key Takeaways by Sector
### Automobile
- **Tata Motors**: Highly volatile; good for short-term trading
- **Maruti Suzuki**: Stable growth; good for long-term investing

### Banking
- **SBI**: High trading volume, more risk
- **HDFC**: Steady performer, less volatile

### IT
- **TCS**: More price swings; attractive to traders
- **Infosys**: Predictable and stable

### Pharma
- **Sun Pharma**: Consistent performer
- **Dr. Reddy’s**: High volatility; sensitive to events

### FMCG
- **HUL**: Some price variation
- **ITC**: Most stable; ideal for conservative investors

---

## 📅 Market Events Considered
- **2020** – COVID-19 crash (impact on auto, banking, boost to pharma)
- **2021** – Post-pandemic recovery (boost in IT and banking)
- **2022-23** – Inflation & interest rates (shift to FMCG)

---

## 📌 How to Run This Project
1. Clone this repository
2. Set up SQL database and import datasets
3. Run the EDA Python script (optional)
4. Open Power BI and connect to the cleaned dataset
5. Explore the dashboards and insights

---

## 🙋‍♀️ About Me
**Soniya Saw**  
Postgraduate in Data Science and Analytics  
Skilled in SQL, Excel, Power BI, Python and Tableau 
Aspiring Data Analyst

---

## 📬 Contact
📧 Email: [soniyamandal@gmail.com]  
📍 Location: India

---

> ⭐ Don’t forget to star this repository if you found it helpful!
