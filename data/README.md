# Data Layer

## Dataset: Online Retail II
This project utilizes the `online_retail_II.xlsx` dataset, containing transactional data from a UK-based online retail store between December 2009 and December 2011.

### Source / Download:
The raw dataset can be downloaded directly from the official UCI Machine Learning Repository:
- [UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online%2Bretail%2Bii)

### Expected Schema (Raw):
- **Invoice:** Invoice number (6 digits). Starts with 'C' for cancellations/returns.
- **StockCode:** Product code (5 digits).
- **Description:** Product (item) name.
- **Quantity:** The quantities of each product per transaction.
- **InvoiceDate:** Invoice date and time.
- **Price:** Unit price in Sterling (£).
- **Customer ID:** Customer number (5 digits).
- **Country:** Country name.
