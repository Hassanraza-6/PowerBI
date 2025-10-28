
# 📦 Inventory Management Dashboard | Power BI Project

A responsive Power BI dashboard that visualizes key inventory KPIs—product stock, reorder levels, shelf-wise distribution, availability percentage, and monthly stock availability trends—to help businesses streamline their inventory management process.

---

## 📚 Table of Contents
- [Project Title](#project-title)
- [Brief One-Line Summary](#brief-one-line-summary)
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Methods](#methods)
- [Key Insights](#key-insights)
- [Dashboard Output](#dashboard-output)
- [How to Run This Project](#how-to-run-this-project)
- [Results & Conclusion](#results--conclusion)

---

## 🏷 Project Title
**Inventory Management Dashboard in Power BI**

---

## ✍️ Brief One-Line Summary
An end-to-end Power BI solution to track inventory movements, highlight low stock alerts, and optimize restocking decisions across shelves and months.

---

## 📌 Overview
This dashboard empowers inventory managers with data-driven visual tools to monitor stock availability, dispatches, and reorder levels across five warehouse shelves. With a clean design and drillable filters, users can immediately identify which products are below threshold and during which months stock levels drop.

---

## ❗ Problem Statement
Manual inventory tracking is inefficient, prone to errors, and lacks real-time monitoring. Businesses often face challenges like overstocking, stockouts, or delayed reorders. This dashboard was created to resolve such issues by offering an automated and visual solution to track and manage inventory efficiently.

---

## 📂 Dataset
- **Source**: Simulated warehouse inventory log  
- **Format**: Embedded `.pbix` file  
- **Fields Included**:
  - Product ID  
  - Product Name  
  - Shelf Number  
  - Quantity in Stock  
  - Reorder Level  
  - Monthly Dispatch  
  - Monthly Received Stock  

---

## 🛠 Tools and Technologies
- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- CSV / Excel (for data source preprocessing)  

---

## 📈 Methods
- Data cleaning & transformation via Power Query  
- DAX measures for:
  - Total Received
  - Total Dispatch
  - Available Stock %
- Interactive filters (slicers) for shelf & product
- Conditional formatting for stock alerts  
- Bar chart (stock trend), donut chart (availability), tables  

---

## 🔍 Key Insights
- 📦 **Total stock received**: 4540 units  
- 📊 **Currently available stock**: 1713 units  
- 🚚 **Total dispatches**: 2827 units  
- 🔄 **Availability rate**: 37.73%  
- 🧾 **Product 8** (P-008) on **Shelf 3** has the highest stock  
- ⚠️ Shelf 1 & Shelf 3 have multiple products close to reorder level  

---

## 📊 Dashboard Output

### 📍 Main View
- 📍 Product Selector and Shelf Filter  
- 📈 Stock Availability Trend (Month-wise)  
- 📊 Donut Chart: % Stock Available  
- 🗃️ Table: Product ID, Shelf, Quantity, Reorder Level  
- 🔢 KPIs: Total Received, Available, Dispatched  

![Inventory Dashboard Snapshot](Snapshot%20of%20Inventory%20Management%20Dashboard.png)

---

## ▶ How to Run This Project

1. Open `Inventory Management Dashboard.pbix` in **Power BI Desktop**
2. All datasets are preloaded — no extra connection needed
3. Use slicers on the left to:
   - Filter products by name or shelf
4. Hover over charts or use visuals to filter insights
5. Use scroll bar in product table for deeper analysis

---

## ✅ Results & Conclusion
This dashboard provides a single-pane view of your inventory KPIs in real time. It:
- Enables better inventory control
- Reduces manual tracking errors
- Improves reorder planning
- Prevents stockouts and overstocking
- Supports warehouse logistics with visual clarity

This is ideal for supply chain analysts, retail inventory teams, and warehouse managers seeking a smart, scalable reporting tool.

