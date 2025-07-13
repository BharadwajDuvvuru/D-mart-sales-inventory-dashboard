# D-mart-sales-inventory-dashboard
Built a Power BI dashboard for a D-Mart-style retail chain to analyze sales, inventory, and wastage.
# D-Mart Sales & Inventory Optimization Dashboard 🛒📊

An end-to-end Business Intelligence (BI) project for a D-Mart-style retail chain. This dashboard empowers stock planning, wastage reduction, and product/category-level revenue insights using Power BI and SQL.

---

## 🔍 Objective

Analyze sales, inventory, and wastage data to uncover:
- High-performing products and underperformers
- Costly inefficiencies in inventory and wastage
- Seasonal revenue trends by category
- Optimized inventory turnover models

---

## 📁 Data Sources

| File Name                     | Description                                  |
|------------------------------|----------------------------------------------|
| `sales_data.csv`             | Daily transaction log per product            |
| `inventory_data.csv`         | Opening stock and movement data              |
| `wastage_data.csv`           | Units wasted and cost per product            |
| `product_master_unique_names.csv` | Product ID to Name + Category mapping    |
| `store_master.csv`           | Store-wise details (if needed for expansion) |
| `Inventory_Turnover.csv`     | Derived KPI data for turnover calculation     |

---

## 🛠 SQL Analysis Highlights (`dmart_sales_data.sql`)

- **Top 10 Best-Selling Products**  
  → Prioritize for stock availability and promos

- **Wastage Cost by Category**  
  → Identify high-loss categories and optimize supply

- **Inventory Turnover Rate**  
  → Calculate product-wise sales efficiency

- **Monthly Revenue by Category**  
  → Detect seasonal demand and top revenue drivers

- **Most Wasted Products**  
  → Use for waste reduction and better demand prediction

---

## 📊 Power BI Dashboard Features

- **KPI Cards**  
  → Total Revenue, Total Units Sold, Inventory Turnover, Wastage Cost

- **Visuals**  
  - Bar Charts: Top Sellers, Top Wastage Products  
  - Line Graph: Monthly Revenue Trend by Category  
  - Heatmap: Time vs Category Revenue  
  - Slicers: Drill by Product, Category, Month

---

## 📈 Business Insights Delivered

- Overstocked slow-movers → high wastage risk  
- 70% of revenue came from limited SKUs in peak months  
- Low inventory turnover linked to higher wastage  
- Recommended shift: from fixed restocking → demand-based restocking

---

## 🧠 Skills Applied

- **SQL (MySQL)**: Joins, group by, views, aggregations  
- **Power BI**: Data modeling, DAX measures, dashboard design  
- **Retail Analytics**: Inventory control, revenue trends, SKU optimization  
- **Data Storytelling**: Converted raw data into actionable business decisions

---

## 👨‍💻 Author

**Bharadwaj Duvvuru**  
*Freelance Data Analyst | BI Developer | SQL + Power BI Specialist*  
📫 Duvvurubharadwaj@email.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bharadwaj-0934442b5/)

---

## 📌 How to Use

1. Import `sales_data.csv`, `inventory_data.csv`, and other CSVs into a MySQL DB (`dmart_sales_data`)
2. Run SQL file: `dmart_sales_data.sql` to create key views and aggregations
3. Open `dmart_sales_data.pbix` in Power BI
4. Refresh data connections → Start exploring interactive reports

---

## 🗓 Timeline

🗂 Duration: Jun 2024   
🧭 Client: Freelance retail BI client (NDA)  
📌 Tools: Power BI, MySQL, Excel

