# Sales-Performance-and-Profit-Analysis-Dashboard

This Power BI project provides a comprehensive, multi-page business intelligence solution designed to analyze sales performance, profitability trends, product rankings, and promotional effectiveness for a nationwide consumer retail portfolio. 

By modeling transactional records, the dashboard empowers sales operations and management teams to instantly pinpoint top revenue-generating products, discover regional trends across India, and conduct flexible, side-by-side historical sales comparisons.

---

##  Core Pages & Analytics Features

### 1. Executive Sales Overview
* **KPI Monitoring:** Keeps a pulse on vital business health indicators: **Total Sales ($122M)**, **Total Profit ($12.2M)**, and **Total Quantity Sold (7.1K units)** across **3,510 total orders**.
* **Geographic Breakdown:** Uses an interactive map layout to visualize regional sales performance across key urban hubs (Delhi, Mumbai, Bangalore, Chennai, etc.).
* **Profit vs. Net Sales Correlation:** Features a scatter plot analysis demonstrating a direct, linear relationship between higher value sales tiers and overall bottom-line margin.
* **Promotion Effectiveness:** A horizontal distribution bar chart mapping total discounts absorbed by specific promotional categories (e.g., Weekend, Clearance, Summer promos).

### 2. Top / Bottom 5 Deep-Dive
* **Product Rankings:** Ranks inventory assets using three critical business lenses: **Total Revenue**, **Volume/Quantity Sold**, and **Net Profitability**.
* **Key Findings:** * Premium electronics serve as primary anchors—the *Apple iPhone 14* alone led performance with **$21.4M in sales** and **$2.14M in profit**.
  * Low-margin consumer staples (e.g., toothpaste, soaps) are flagged at the bottom tiers to signal potential stock bundling or pricing revision opportunities.

### 3. Dynamic Period Comparison
* **Dual Date Slicers:** Implements independent date parameters allowing users to evaluate performance anomalies between two entirely different custom timeframes side-by-side.

### 4. Transaction Ledger
* **Granular Audit Trail:** Houses a clean tabular data matrix for flat-file exploration, exposing Customer IDs, Order IDs, accurate unit prices, promotional code impacts, and net sales per item.

---

## Technical Stack & Data Model
* **BI Platform:** Power BI Desktop
* **Data Modeling:** Star Schema architecture utilizing relational dimension tables linked to core transaction fact tables.
* **Storage Mode:** Import Mode (Optimized for fast in-memory DAX calculations and swift visualization interactions).
* **Advanced DAX Concepts:** Used to handle custom time-intelligence comparison logic and custom top/bottom product rankings.

---

##  How to Navigate the Dashboard
1. **To audit products:** Head over to the `Top/Bottom 5 Analysis` tab to immediately identify items keeping your margins afloat vs. items costing warehouse space.
2. **To run time-period comparisons:** Navigate to the comparison tabs, adjust `Date Filter 1` and `Date Filter 2` to your target quarters/years, and observe variations instantly across the dual bar charts.(b)Helped identify low-performing products and ineffective promotions.






