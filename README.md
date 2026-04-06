# Bootcamp Enrollment Analysis & Demand Forecasting

## Overview
This project analyzes bootcamp enrollment data to understand demand patterns, identify growth drivers, and forecast short-term enrollment across multiple programs.  
The goal is to support **data-driven batch planning, marketing strategy, and product portfolio decisions**.

---

## Problem
Bootcamp enrollment fluctuates across products and time.  
Without structured analysis, it is difficult to determine:

- which products drive the majority of demand
- how marketing channels influence enrollment
- how future demand may evolve in the short term

---

## Approach
The project was conducted in three main stages:

1. **Data Preparation**
   - Cleaning inconsistent categorical values
   - Handling empty strings and placeholders
   - Aggregating enrollment into monthly product-level data

2. **Exploratory Data Analysis**
   - Product performance analysis
   - Channel and geographic distribution
   - Demographic and motivation insights
   - Demand trend and volatility analysis

3. **Forecasting**
   - Time-series forecasting per product
   - Evaluation using MAE, RMSE, and SMAPE
   - 3-month enrollment projection for key programs

---

## Key Insights
- **Data Science** is the highest-performing program with nearly **2× enrollment** compared to the second-highest product.
- Enrollment growth appears **campaign-driven rather than seasonal**, with spikes linked to marketing pushes.
- **Instagram and referral channels** drive the majority of enrollments.
- Most participants are **early-career professionals (age 20–30)** seeking **career advancement**.
- Short-term forecasting reveals **three demand tiers** across programs.

---

## Tools & Technologies
- **Python** (Pandas, NumPy)
- **Time Series Forecasting** (Naïve, MA3, ARIMA (non-seasonal), SARIMA, ETS)
- **Data Visualization** (Matplotlib, Seaborn)
- **Power BI / Dashboard**

---

## Explore The Outcome

👉 [Power BI](https://app.powerbi.com/view?r=eyJrIjoiOTExNmQ5NTAtN2Y1Yy00OWJjLWE5MDUtYzg1NjczMTcxN2VlIiwidCI6ImExYjZmMzMyLThlMzEtNDIwMS1hMDNhLTE2MzBmMWRiYTBlNSJ9)

👉 [Presentation](https://github.com/sna-ds/internpro/blob/main/Sales%20Internpro.pdf)
