# Sales Trend Dashboard Project 📊

## Overview
This project analyzes online store sales data using Excel to create a **Sales Trend Dashboard**. The dashboard provides insights into top-selling categories, monthly sales trends, and profit distribution, helping businesses make data-driven inventory and pricing decisions.

The dataset used for this project is included in the file:  
`DownloadnSales_Trend_Dashboard_50Rows.xlsx` (50 sample rows).

---

## Features
The dashboard includes **three main Pivot Tables**:

1. **Top-Selling Categories**
   - Rows: Category  
   - Values: Sum of Revenue  
   - Sorted Largest to Smallest  
   - Shows which product categories generate the most revenue.

2. **Monthly Sales Trend**
   - Rows: Month  
   - Values: Sum of Revenue  
   - Visualizes monthly revenue trends.

3. **Profit by Category**
   - Rows: Category  
   - Values: Sum of Total Profit  
   - Highlights profit distribution across categories.

---

## Tools & Technologies
- **Microsoft Excel** (Pivot Tables, Formulas, Power Query)  
- Dataset Columns:
  - `order_date` – Date of the order  
  - `product_id` – Unique product identifier  
  - `category` – Product category  
  - `product_name` – Product name  
  - `Revenue` – Total revenue per order  
  - `Profit_per_unit` – Profit earned per unit sold  
  - `Total_Profit` – Total profit per order  
  - `Month` – Month extracted from order_date  
  - Other columns: `Sum of order_id`, `Sum of price`, `Sum of quantity`, `Sum of cost`

---

## How to Use
1. Open `DownloadnSales_Trend_Dashboard_50Rows.xlsx` in Excel.  
2. Ensure all data is cleaned and formatted:
   - `order_date` → Date format  
   - `price`, `quantity`, `cost` → Number format  
   - Revenue and Profit columns calculated.  
3. Insert Pivot Tables for analysis:
   - Top-Selling Categories  
   - Monthly Sales Trend  
   - Profit by Category  
4. Optionally, use **Excel charts** to visualize insights (e.g., column charts, line graphs).

---

## Insights & Recommendations
- Identify **best-selling categories** to prioritize inventory.  
- Track **monthly sales trends** to understand seasonal demand.  
- Analyze **profit distribution** to focus on high-margin products.  
- Potential **inventory optimization** could improve stock availability by ~15%.

---

## File Structure
Sales_Trend_Dashboard_Project/
- DownloadnSales_Trend_Dashboard_50Rows.xlsx
- README.md
