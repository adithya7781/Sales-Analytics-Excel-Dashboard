# Sales Analytics Excel Dashboard

![Excel](https://img.shields.io/badge/Microsoft%20Excel-Advanced-217346?logo=microsoft-excel&logoColor=white) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen) ![Domain](https://img.shields.io/badge/Domain-Business%20Analytics-orange)

> A fully interactive Business Analytics Dashboard built in Microsoft Excel, consolidating multi-source sales data across retail, online, regional, inventory, and customer dimensions into a single decision-ready reporting layer.

---

## Overview

This project transforms raw, fragmented sales data from five distinct sources into a unified Excel dashboard with dynamic charts, KPI summaries, and slicers. It demonstrates advanced Excel skills including multi-table data modeling, PivotTables, conditional formatting, and business storytelling through data — without any external BI tool.

---

## Repository Structure

```
Sales-Analytics-Excel-Dashboard/
│
├── Data/
│   ├── Customer-Purchase-History.xlsx       # Customer-level transaction records
│   ├── Inventory-Tracking.xlsx              # Stock levels, reorder points, turnover
│   ├── Online-Store-Orders.xlsx             # E-commerce order data
│   ├── Product-Sales-Region.xlsx            # Region-wise product sales
│   └── Retail-Store-Transactions.xlsx       # In-store POS transaction data
│
├── Business_Analytics_Dashboard.xlsx        # Master dashboard (all analysis + visuals)
├── Business_Analytics_Dashboard.pdf         # Exported static view of the dashboard
└── README.md
```

---

## Data Sources

| File | Description | Key Fields |
|------|-------------|------------|
| `Customer-Purchase-History.xlsx` | Repeat purchase patterns and customer segments | Customer ID, Purchase Date, Amount, Category |
| `Inventory-Tracking.xlsx` | Stock movement and reorder status | Product ID, Stock Level, Reorder Point, Turnover Rate |
| `Online-Store-Orders.xlsx` | E-commerce channel orders | Order ID, Channel, Product, Revenue, Date |
| `Product-Sales-Region.xlsx` | Geographic breakdown of product performance | Region, Product, Units Sold, Revenue |
| `Retail-Store-Transactions.xlsx` | Brick-and-mortar POS data | Transaction ID, Store, Date, Product, Amount |

---

## Dashboard Features

### KPI Summary Panel
- Total Revenue, Total Orders, Average Order Value
- Month-over-Month and Year-over-Year growth indicators
- Top-performing product and region at a glance

### Sales Trend Analysis
- Monthly revenue line chart with trendline
- Channel comparison (Online vs. Retail) over time
- Seasonal demand spike detection

### Regional Performance
- Region-wise revenue bar chart
- Best and worst performing territories
- Product-level drilldown by region

### Product Analytics
- Top 10 products by revenue and units sold
- Category-level contribution breakdown (Pareto chart)
- Slow-moving vs. fast-moving SKU identification

### Customer Insights
- Repeat vs. new customer split
- Purchase frequency distribution
- High-value customer segment analysis

### Inventory Health
- Current stock vs. reorder threshold
- Overstock and stockout risk flags
- Inventory turnover ratio by product

---

## Excel Techniques Used

- **PivotTables & PivotCharts** — Dynamic aggregation across all five data sources
- **VLOOKUP / XLOOKUP / INDEX-MATCH** — Cross-table data retrieval
- **Slicers & Timelines** — Interactive filtering by region, category, date
- **Conditional Formatting** — Visual flagging of performance thresholds
- **Named Ranges & Data Validation** — Structured, error-resistant inputs
- **Advanced Formulas** — SUMIFS, COUNTIFS, AVERAGEIFS, dynamic arrays
- **Dashboard Layout Design** — Clean, print-ready layout with no gridlines

---

## How to Use

1. Clone or download the repository
2. Open `Business_Analytics_Dashboard.xlsx` in **Microsoft Excel 2016 or later**
3. Enable editing and macros if prompted
4. Use the **slicers** (Region, Category, Date) to filter the entire dashboard dynamically
5. Raw data files are in the `/Data/` folder — update them to refresh all visuals automatically

> For a static preview without Excel, open `Business_Analytics_Dashboard.pdf`.

---

## Key Insights

- **Online orders** outpaced retail transactions in Q3 and Q4, signaling a channel shift worth acting on
- **3 out of 5 regions** contributed over 80% of total revenue, highlighting geographic concentration risk
- A small cluster of **high-frequency customers** (top 15%) drove ~45% of repeat revenue — strong retention target
- Several SKUs showed **consistent overstock**, tying up working capital with low turnover rates

---

## Author

**Ketharaju Vishal Adithya**  
B.Tech Data Science, Vignana Bharathi Institute of Technology (VBIT), Hyderabad  
[GitHub](https://github.com/adithya7781)

---

## License

This project is intended for portfolio and educational demonstration purposes.
