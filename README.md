# Task 3 - RFM Customer Segmentation
**Internship Track:** Data Analytics — Elevvo Pathways

## 🎯 Objective
Use RFM (Recency, Frequency, Monetary) analysis to segment customers from retail sales data for marketing purposes.

## 📂 Dataset
- Source: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
- File: `Online Retail.xlsx`

## 🧹 Data Cleaning
- Removed null CustomerIDs
- Dropped duplicates and cancelled invoices
- Created TotalPrice = Quantity × UnitPrice

## 🧮 RFM Scoring
- Recency: Days since last purchase
- Frequency: Number of invoices
- Monetary: Total spend
- Scored using quantiles (1–5 scale)
- Created customer segments (e.g., Top, Loyal, At Risk)

## 📊 Visuals
- Distribution of RFM Scores
- Segment-based grouping (bar chart)

## 🛠️ Tools Used
- Python
- Pandas
- Seaborn / Matplotlib (optional)

## 🔍 Key Insights
- Identified high-value and loyal customer groups
- Suggested re-engagement for inactive segments

> Part of the Elevvo Data Analytics Internship — August 2025
