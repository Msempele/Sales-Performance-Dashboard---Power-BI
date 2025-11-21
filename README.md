# 📊 Sales Performance Dashboard — Power BI

This project analyzes company sales performance across regions, product categories, customers, and time using Power BI. It demonstrates end-to-end BI skills including data modeling, Power Query transformation, DAX calculations, and dashboard design for business insights.

---

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | KPI calculations & time intelligence |
| **Excel** | Source dataset & preprocessing |

---

## 🗂 Dataset Overview

The dataset used is synthetic and includes five tables modeled into a star schema:

| Table | Description |
|-------|-------------|
| **FactSales** | Transaction-level sales data |
| **DimProduct** | Product info (category, cost, price) |
| **DimRegion** | Sales region mapping |
| **DimCustomer** | Customer details |
| **DimDate** | Calendar table for time intelligence |

### Key Columns in `FactSales`

| Column | Meaning |
|--------|---------|
| `SalesAmount` | UnitPrice × Quantity |
| `Cost` | Cost per unit |
| `Profit` | SalesAmount − (Cost × Quantity) |
| `Quantity` | Units sold per transaction |

---

## 📐 Data Model (Star Schema)
<img width="808" height="757" alt="assetsdata_model" src="https://github.com/user-attachments/assets/29806bcd-6eb6-48a5-b8fc-0422d99aeefe" />


---

## 📊 Visuals Included

| Visual | Purpose |
|--------|---------|
| **KPI Cards** | High-level summary of performance |
| **Sales by Region (Bar Chart)** | Compare performance across regions |
| **Profit by Category (Bar Chart)** | Identify most profitable product categories |
| **Sales Trend Over Time (Line Chart)** | Seasonal & temporal patterns |
| **Top Products Table** | Product-level profitability insights |
| **Slicers Panel** | Interactive filtering (Quarter, Region, Category)

---

## 📱 Dashboard Preview
<img width="1373" height="770" alt="Dashboard" src="https://github.com/user-attachments/assets/8433a19c-f956-4ddd-a3e2-5b1c67c5291e" />

---

## 🧠 Insights

- **Coast region generated the highest revenue (251K)** followed by Rift Valley (227K).
- **Category C is the most profitable category (145K)**, significantly outperforming B (109K) and A (82K).
- **Sales peaked in August (~118K)**, while March recorded the lowest performance (~70K), indicating monthly demand fluctuations.
- **Product 15 contributed the highest revenue (66K)**, with Products 4 and 9 close behind.

---

## 🚀 Skills Demonstrated

- Data modeling (Relationship building, star schema)
- Power Query data transformation
- Time intelligence using DAX
- Report design & data storytelling
- Portfolio-ready documentation

---

## 📎 How to Run This Project

1. Clone the repository or download files
2. Open `sales_dashboard.pbix` in Power BI Desktop
3. Ensure dataset paths are relative
4. Refresh to load model

---

## 🔮 Future Enhancements

- Add forecasting trends
- Include territory-level drillthrough pages
- Add customer segmentation and retention metrics
- Publish interactive version publicly

---

## ⭐ Author

**Melvin Sempele**  
Business Intelligence & Data Analyst  
📍 Nairobi, Kenya
---
