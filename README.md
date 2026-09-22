# 🛒 E-Commerce Demand & Inventory Intelligence (Online Retail II)

> End-to-end data analytics and inventory optimization pipeline built on historical retail transactions.

---

## 📌 1. Business Problem
In e-commerce operations, traditional reporting only answers *what happened*. Supply chain and inventory managers need to answer:
1. *What is the underlying demand trend, independent of returns and cancellations?*
2. *Which customer segments drive the core revenue (RFM Analysis)?*
3. *How can we prevent stockouts without holding excess inventory?*

This project tackles these challenges by transforming raw transactional data into an analytical model, forecasting logic, and automated business alerts.

---

## 🏗️ Architecture & Evolution
The project is structured in two architectural phases to ensure clean separation between local development and cloud scalability:

- **Phase 1 (MVP / Local):** Python/Pandas ETL $\rightarrow$ PostgreSQL $\rightarrow$ Advanced SQL Analytics $\rightarrow$ Power BI $\rightarrow$ n8n.
- **Phase 2 (Cloud Scale):** Migration to AWS Data Lake (S3), AWS Glue processing, and Amazon Athena serverless queries.

---

## 📂 3. Repository Structure (Current State)
```text
demand-forecasting-inventory/
│
├── README.md                 # Project Overview & Case Study
├── data/
│   └── README.md             # Dataset documentation (Online Retail II - 2009-2011)
└── docs/
    └── architecture.md       # Pipeline architecture diagram & evolution plan

## 📊 4. Dataset Overview

* **Source:** Online Retail II (UCI Machine Learning Repository / Kaggle mirror).
* **Scope:** Two years of transactional data (01/12/2009 to 09/12/2011) from a UK-based online retail company.
* **Granular structure:** Invoice numbers, StockCodes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

Project developed as part of a Data Analytics & Engineering portfolio.
