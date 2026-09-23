# 🛒 E-Commerce Demand & Inventory Intelligence (Online Retail II)

> End-to-end data analytics, demand forecasting, and inventory optimization pipeline built on historical retail transactions using Advanced SQL, PostgreSQL, Advanced Excel (Monte Carlo Simulations), Power BI, and AWS.

---

## 📌 1. Business Problem & Objectives
In e-commerce and retail operations, traditional reporting only answers what happened. Supply chain and inventory managers need answers for forward-looking decisions:
1. **Demand Trend & Seasonality:** What is the underlying product demand over time, independent of returns and cancellations?
2. **Demand Forecasting & Incerteza:** How can we project future sales trends and simulate demand variability using **Monte Carlo simulations in Advanced Excel**?
3. **Inventory Intelligence:** When and how much should we reorder? (Calculating **Safety Stock** and **Reorder Points** under uncertainty to prevent stockouts without holding excess inventory).
4. **Customer Segmentation:** Which customer segments drive core revenue? (RFM Analysis).

This project tackles these challenges by transforming raw transactional data into an analytical PostgreSQL model, structured SQL queries, Excel-based stochastic forecasting models, and executive dashboards.

---

## 🏗️ Architecture & Evolution
The project is structured in two architectural phases:
- **Phase 1 (MVP / Local):** Data Validation -> PostgreSQL Storage -> Advanced SQL Analytics -> **Excel (Monte Carlo Demand Simulation & Inventory Logic)** -> Power BI -> n8n Automation.
- **Phase 2 (Cloud Scale):** Migration to AWS Data Lake (S3) and Amazon Athena serverless queries.

---

## 📂 2. Repository Structure
```text
demand-forecasting-inventory/
│
├── README.md                 # Project Overview & Case Study
├── data/                     # Dataset documentation (Online Retail II)
├── docs/                     # Architecture diagram & data quality rules
├── sql/                      # Analytical queries, cleaning, RFM & aggregation logic
└── excel/                    # Demand forecasting models & Monte Carlo simulations
```

---

## 📊 3. Dataset Overview
- **Source:** Online Retail II (UCI Machine Learning Repository).
- **Scope:** Two years of transactional data (01/12/2009 to 09/12/2011) from a UK-based online retail company.
- **Granular structure:** Invoice numbers, StockCodes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

---
*Project developed as part of a Data Analytics & Engineering portfolio.*
