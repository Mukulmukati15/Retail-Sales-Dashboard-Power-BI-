# 🛍️ Retail Sales Dashboard (Power BI)

This project is a dynamic and interactive **Retail Sales Dashboard** built using **Power BI**. It leverages two core data tables — `Orders` and `Details` — to visualize and analyze sales performance across product categories, regions, time periods, and payment methods.

---

## 📁 Data Sources

- `orders.xlsx`: Contains customer and order-level data  
  *(Order ID, Order Date, Customer Name, State, City, Payment Mode, etc.)*

- `details.xlsx`: Contains product-level sales data  
  *(Order ID, Category, Sub-Category, Quantity, Amount, Profit, etc.)*

The two tables are linked via **Order ID** using relationships in Power BI.

---

## 📊 Dashboard Features

- 📈 **Monthly Profit Trends**
- 🛒 **Category & Sub-Category Sales Breakdown**
- 💳 **Payment Mode Analysis**
- 🧾 **Quantity Sold by Category & Payment Type**
- 🗺️ **State-wise & City-wise Sales Performance**
- 🔍 **Interactive Filters**: Category, State, City, Month, Payment Mode

---

## 📌 Key Insights

- Identified high-profit and high-volume categories
- Compared performance of different sub-categories
- Analyzed customer purchasing patterns by payment mode
- Detected monthly fluctuations in total sales and profit

---

## 🧰 Tools & Techniques

- **Power BI Desktop**
- Data Modeling & Relationships
- DAX Measures for Profit, Quantity, Sales
- Visuals: Bar Charts, Line Graphs, Pie Charts, Maps, KPI Cards
- Slicers for enhanced interactivity
