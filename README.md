🛒 Supermarket Sales Analysis | Power BI + DAX
FULL INTRACTIVE DASHBOARD DOWNLOAD FOR BETTER VIEW REAL TIME CHANGES 

[ https://github.com/H-cyber-bit/Maven-Market-Analysis./blob/main/Market%20Maven%20Analysis.pbit ]



A deep-dive data project where complex, raw supermarket sales data is transformed into **business-ready insights** using Power BI, DAX, and dimensional modeling. This report captures performance across 2 years of retail transactions — tracking revenue, returns, profit margins, order volume, and customer behavior.

---

📁 Dataset Overview

The dataset contains transactional sales records across multiple years and stores — mimicking real-world B2C retail operations.

Key data points:
- 🏪 Store IDs, Names, Regions
- 📦 Products, Brands, Quantities
- 📅 Orders: Dates, Processing Days, Returns
- 💰 Sales, Returns, Net Profit

> Total Sales: **$1.76M**  
> Total Profit: **$1.05M**  
> Total Quantity Ordered: **833K**  
> Period Covered: **1997–1998**

---

 🧹 Data Handling & Modeling

This wasn’t drag-drop-done. We built this like a pro.

 ✅ Step-by-Step Data Handling:
1. **Imported** multiple flat CSV tables
2. **Cleaned** nulls, duplicates, mismatched data types
3. Standardized columns (e.g., date formats, region names)
4. Created a **star schema** with fact/dimension separation
5. Built proper **one-to-many relationships**:
   - Store ↔ Sales
   - Product ↔ Returns
   - Time Table ↔ Orders

🧰 Power Query Tasks:
- Replaced erroneous `null` values in sales/profit columns
- Removed duplicate entries in transaction logs
- Created a **date dimension** manually (with fiscal mapping)
- Generated new columns: `Month Name`, `Day Name`, `Year`, `Store Region`

---

SALES ANALYSIS IMAGE - [https://github.com/H-cyber-bit/Maven-Market-Analysis./blob/main/Sales%20Analysis.png]

ORDER ANALYSIS IMAGE - [ https://github.com/H-cyber-bit/Maven-Market-Analysis./blob/main/Order%20Analysis.png ]

RETURN ANALYSIS IMAGE - [ https://github.com/H-cyber-bit/Maven-Market-Analysis./blob/main/Return%20Analysis.png]
                  

 🧠 DAX Measures

Power BI's muscle comes from DAX. These were custom-built for the visuals:

DAX
Net Sales = [Total Sales] - [Return Value]

Total Profit = SUM('Sales'[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Avg Order Quantity = AVERAGE('Sales'[Quantity])

Return Rate % = DIVIDE([Return Quantity], [Quantity], 0)

Sales Growth % =
DIVIDE(([Total Sales 1998] - [Total Sales 1997]), [Total Sales 1997], 0)


Advanced logic also handled:

* **Time-intelligence** across years
* **Brand-wise aggregations**
* **Return impact per store and product**
* **Goal performance benchmarking**

--

 📊 Dashboard Design & Visuals

The report is structured into **multiple insight zones**, each serving a unique business purpose:

 💼 Executive Summary

* Net Sales, Total Orders, Profit Margin
* Sales Growth YoY
* Return Rate % and Total Returns

 🏬 Store Performance

* Sales & Profit by Store
* Avg Order Value by Store
* Processing Days by Store

 🛍️ Product & Brand Trends

* Top 10 Performing Brands (1997 vs 1998)
* Quantity vs Revenue Analysis
* Profitability by Product Group

 🌎 Regional Trends

* Sales & Profit by Region
* City-wise Customer Concentration

 🔁 Returns & Losses

* Monthly & Product-Wise Return Breakdown
* Return Impact on Net Sales
* Store-wise return patterns
* Return Days Analysis



---

# 💡 Business Insights

* 🏆 Store 13 led with highest profit (\~\$101K)
* 📈 Sales grew by **\$177K** in 1998 compared to 1997
* 🧃 “Washington Cream Soda” had the highest return rate — product issue?
* 🌆 Cities like **Spokane, Olympia** dominated in order frequency
* 📦 Return rate was kept under 1% — indicating solid logistics & satisfaction
* 🕒 Avg processing time hovered around 4 days — consistent across stores

---

## ⚙️ Tech Stack

| Area          | Tool                              |
| ------------- | --------------------------------- |
| Data Cleaning | Power Query Editor                |
| Modeling      | Star Schema, Relationships        |
| Calculations  | DAX                               |
| Visuals       | Bar, Line, Matrix, Cards, Slicers |
| Tools         | Power BI Desktop                  |

---

 🚀 Why This Project Matters

This isn't just a dashboard — it’s a **complete BI solution**: from raw data to strategic decision-making insights. It shows my ability to:

* Model and clean real-world business data
* Write accurate and optimized DAX
* Extract performance drivers across regions, products, and time
* Design user-friendly, executive-ready reports in Power BI

> A great fit for any role where data needs to **speak for itself**.

---

## 👋 Connect With Me

Let’s talk about building better insights from data:
📧 [harsh201130@gmail.com](mailto:harsh201130@gmail.com)
🔗 [LinkedIn – Harsh Sharma](https://www.linkedin.com/in/harsh-sharma-354379294/)



You're building a **killer BI portfolio**, Harsh. Let’s keep the momentum. 🚀
```
