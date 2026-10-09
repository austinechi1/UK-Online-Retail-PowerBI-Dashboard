# UK Online Retail Performance Dashboard

> **Power BI business intelligence case study analysing retail revenue, customer behaviour, product performance, and returns using Power Query, DAX, data modelling, and interactive reporting.**

**[Download the interactive Power BI report (.pbix)](UK_Online_Retail_Dashboard.pbix)** · [View dashboard screenshots](#dashboard-pages)

![Overview Dashboard](01_Overview_Dashboard.png)

## Executive Summary

This three-page Power BI report transforms transactional retail data into a decision-support dashboard focused on **sales performance, customer value, product contribution, and returns**.

The analysis is designed around practical business questions rather than visualisation alone: where revenue comes from, which customers and products drive value, and where returns may create commercial risk.

## Business Questions

- How much revenue and gross sales did the business generate?
- How are sales and returns changing over time?
- Which products, customers, and countries contribute the most revenue?
- What is the average order value and revenue per customer?
- Which customer groups generate the most value?
- Which products and countries generate the highest return value?
- What proportion of return transactions comes from cancelled orders?

## Dashboard Pages

### 1. Overview
High-level KPIs for net revenue, gross sales, orders, active customers, average order value, return rate, monthly revenue, leading products, and countries.

![Overview Dashboard](01_Overview_Dashboard.png)

### 2. Product & Customer Analysis
Explores product contribution and customer value using revenue, unit-sales, revenue-per-customer, leading-customer analysis, and customer segmentation.

![Product and Customer Analysis](02_Product_Customer_Analysis.png)

### 3. Returns Analysis
Examines return value, return rate, returned units, monthly return patterns, products, geography, and return type.

![Returns Analysis](03_Returns_Analysis.png)

## Key Findings

- **Net revenue:** £9.77M
- **Gross sales:** £10.67M
- Approximately **20K orders**
- Approximately **4K active customers**
- Approximately **4K distinct products**
- **Average order value:** £534.40
- **Revenue per customer:** approximately £2.25K
- The **United Kingdom** was the dominant market by revenue.
- **DOTCOM POSTAGE** was the highest-revenue product in the overall analysis.
- The high-value customer group generated approximately **32% of total revenue**.
- **Return value:** approximately £896.81K
- **Return rate:** 8.4%
- Cancelled orders represented approximately **74% of return transactions**.

## Business Interpretation

The dashboard highlights three important management themes:

1. **Revenue concentration:** a relatively small group of high-value customers contributes a significant share of revenue.
2. **Market concentration:** the UK is the dominant market, creating both a strong core market and a concentration consideration.
3. **Returns:** the value and cancellation mix of returns deserves operational investigation because it can affect reported revenue and fulfilment efficiency.

## Data Preparation

Power Query was used to:

- Clean and trim text fields
- Remove errors and empty records
- Standardize data types
- Create sales and return classifications
- Prepare date, customer, product, country, quantity, and revenue fields

## Data Model

The model contains a central `FactSales` table connected to a dedicated `DateTable`. A disconnected `Customer Segments` table supports dynamic customer segmentation measures.

![Data Model](04_Data_Model.png)

## DAX & BI Techniques

The report includes measures for:

- Net Revenue and Gross Sales
- Total Orders and Active Customers
- Average Order Value
- Revenue per Customer
- Month-over-month KPI trends
- Total Returns and Return Rate
- Returned Units and Return Value
- Customer segment counts and revenue share
- Cancelled-order share of returns
- Dynamic trend labels and conditional formatting

## Interactive Features

- Year and country slicers
- Cross-filtering between visuals
- Page-navigation buttons
- Dynamic month-over-month indicators
- Conditional trend formatting
- Customer segmentation

## Tools

**Power BI Desktop · Power Query · DAX · Data Modelling · Data Visualisation**

## Repository Structure

```text
UK-Online-Retail-PowerBI-Dashboard/
├── 01_Overview_Dashboard.png
├── 02_Product_Customer_Analysis.png
├── 03_Returns_Analysis.png
├── 04_Data_Model.png
├── UK_Online_Retail_Dashboard.pbix
└── README.md
```

## How to Review

Open the [Power BI report](UK_Online_Retail_Dashboard.pbix) in Power BI Desktop to explore the complete interactive report and DAX model. The PNG exports provide a quick preview without requiring Power BI.

## Author

**Nwachukwu Austine**  
Data Analyst | Power BI | SQL | Python

[GitHub](https://github.com/austinechi1) · [Portfolio](https://austinechi1.github.io/)
