# Architecture & Project Evolution

The project is designed to evolve gracefully from a local MVP into a production-grade cloud solution.

## Phase 1 (MVP / Local)
- **Data Source:** `online_retail_II.xlsx`
- **Storage & Modeling:** PostgreSQL / Local DB
- **Analytics & Forecast:** Python & Monte Carlo Simulations
- **Consumption:** Power BI Dashboard
- **Action & Alerts:** n8n (Operational Automation)

## Phase 2 (Cloud Scale)
- **Data Source:** `online_retail_II.xlsx`
- **Cloud Storage:** AWS S3 (Raw & Curated layers)
- **Processing:** AWS Glue
- **Querying:** Amazon Athena (Serverless SQL)
- **Consumption:** Power BI
