# 🛒 E-Commerce Demand & Inventory Intelligence (Online Retail II)

> End-to-end data analytics and inventory optimization pipeline built on historical retail transactions using Advanced SQL, PostgreSQL, Power BI, and AWS.

---

## 📌 1. Business Problem
In e-commerce operations, traditional reporting only answers *what happened*. Supply chain and inventory managers need to answer:
1. *What is the underlying demand trend, independent of returns and cancellations?*
2. *Which customer segments drive core revenue (RFM Analysis)?*
3. *How can we structure analytical queries and database models to support inventory decisions?*

This project tackles these challenges by transforming raw transactional data into an analytical PostgreSQL model, structured SQL queries, and executive dashboards.

---

## 🏗️ Architecture & Evolution
The project is structured in two architectural phases:
- **Phase 1 (MVP / Local):** Excel Validation $
ightarrow$ PostgreSQL $
ightarrow$ Advanced SQL Analytics $
ightarrow$ Power BI $
ightarrow$ n8n.
- **Phase 2 (Cloud Scale):** Migration to AWS Data Lake (S3) and Amazon Athena serverless queries.

---

## 📂 2. Repository Structure
```text
demand-forecasting-inventory/
│
├── README.md                 # Project Overview & Case Study
├── data/                     # Dataset documentation (Online Retail II)
├── docs/                     # Architecture diagram & data quality rules
└── sql/                      # Analytical queries, data cleaning & RFM logic
```

---

## 📊 3. Dataset Overview
- **Source:** Online Retail II (UCI Machine Learning Repository).
- **Scope:** Two years of transactional data (01/12/2009 to 09/12/2011) from a UK-based online retail company.
- **Granular structure:** Invoice numbers, StockCodes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

---
*Project developed as part of a Data Analytics & Engineering portfolio.*

