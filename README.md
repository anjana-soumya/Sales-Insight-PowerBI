# Sales Insights Dashboard | Power BI + MySQL

## Overview

This project is an interactive Sales Insights Dashboard developed using Power BI. The dashboard connects to a MySQL database and provides business intelligence on sales performance, revenue trends, customer analysis, product performance, and market-wise insights.

The project demonstrates the complete Business Intelligence workflow:
- Data Storage in MySQL
- Data Transformation using Power Query
- Data Modeling
- DAX Measure Creation
- Interactive Dashboard Design

---

## Dashboard Preview


![Dashboard](images/dashboard.png)

---

## Features

- Revenue KPI Card
- Sales Quantity KPI Card
- Revenue by Market
- Sales Quantity by Market
- Top 5 Customers by Revenue
- Top 5 Products by Revenue
- Revenue Trend Analysis
- Date and Month Slicers for interactive filtering
- Dynamic cross-filtering across all visuals

---

## Tech Stack

- Power BI Desktop
- MySQL
- Power Query
- DAX
- SQL

---

## Database

The project uses a MySQL database named **sales** containing the following tables:

- customers
- products
- transactions
- markets
- date

The complete database is available in:

```
db_dump.sql
```

---

## Dashboard Metrics

- Total Revenue
- Total Sales Quantity
- Revenue by Market
- Sales Quantity by Market
- Top Customers
- Top Products
- Monthly Revenue Trend

---

## How to Run

### 1. Import Database

Open MySQL Workbench and execute:

```
db_dump.sql
```

This creates the **sales** database along with all required tables and sample data.

### 2. Open Power BI

Open

```
Sales-Insights-Dashboard.pbix
```

### 3. Update Data Source

If prompted,

- Server: localhost
- Database: sales
- Enter your MySQL credentials

Refresh the report.

---

## Learning Outcomes

- MySQL database integration with Power BI
- Data cleaning using Power Query
- Data modeling and relationships
- DAX measure creation
- Interactive dashboard development
- Business KPI visualization

---

## Future Improvements

- Profit Analysis
- Regional Drill-through Reports
- Customer Segmentation
- Forecasting
- Row-Level Security (RLS)
- Power BI Service Deployment
