# 💼 Advanced Financial Analytics Dashboard in Power BI

## 📖 Project Overview
The **Advanced Financial Analytics Dashboard in Power BI** is a comprehensive and interactive data visualization project designed to help stakeholders make **data-driven financial and business decisions**.

This project consolidates **financial, sales, customer, and operational metrics** into seven interlinked dashboards, providing a unified 360° business intelligence view.  
It helps track performance across key areas such as customer activity, transaction flow, product profitability, sales team effectiveness, and year-on-year financial trends.

---

## 🎯 Objective
The goal of this project is to:
- Demonstrate how to **design and develop a multi-page Power BI report** with **interconnected dashboards**.
- Showcase **advanced DAX calculations**, **data modeling**, and **interactive visual storytelling** techniques.
- Provide actionable insights for business leaders through clean, dynamic, and user-friendly dashboards.

---

## 🧩 Key Features
✅ Seven dashboards connected through a **centralized home page**  
✅ **Interactive slicers** for real-time filtering (Year, Sales Team, Channel, Region, etc.)  
✅ **Drill-through and page navigation buttons** for seamless user experience  
✅ **Dynamic visuals** powered by advanced **DAX measures** and **Power Query transformations**  
✅ Fully **responsive dashboard design** with consistent color theme, layout, and KPI alignment  

---

## 🏠 Dashboard Structure

### 🗂️ 1. Home Page – Dashboard Navigation Hub
The **Home Page** acts as the central control panel linking to all dashboards.  
It provides a structured navigation layout for users to easily explore key performance areas.

📸 *Insert Image Below*  
![Home Page Preview](images/homepage.png)

---

### 👥 2. Customer Analysis Dashboard
The **Customer Analysis Dashboard** helps understand customer behavior, retention patterns, and purchasing frequency.

**Key Metrics & Visuals:**
- Total Number of Customers  
- Total Transactions  
- Table: *Customer Name*, *Last Purchase Date*, *Days Since Last Purchase (SLP)*, *Total Transactions*  
- Top 5 Customers for Retargeting  
- Year Slicer: *(2018, 2019, 2020)*  

**Business Insight:**  
Helps identify loyal and inactive customers for retargeting campaigns and retention strategies.

---

### 💳 3. Transaction Analysis Dashboard
Analyzes transaction patterns, shipping and delivery efficiency, and revenue contribution by channel.

**Key Metrics & Visuals:**
- Total Orders by Month  
- Shipping Status Breakdown: *Early, Late, Very Late Shipping*  
- Delivery Status: *Quick, Late, Very Late Delivery*  
- Sales Channels: *In-store, Online, Distributor, Wholesale*  
- KPIs: *Gross Profit*, *Gross Revenue*, *Quantity Ordered*  
- Filters: *Year*, *Sales Team*  

**Business Insight:**  
Tracks supply chain efficiency, highlights delays, and identifies sales channel performance variations.

---

### 📦 4. Product Analysis Dashboard
Provides insights into product-level profitability and performance.

**Key Metrics & Visuals:**
- Top 5 Products by Revenue  
- Top 5 Products by Profit  
- Top 5 Product Revenues by Sales Channel  
- Product Table:  
  *Sum of Unit Price*, *Unit Cost*, *Gross Profit*, *COGS*, *Total Revenue*, *Order Quantity*, *Transactions*, *Product Name*  

**Business Insight:**  
Supports product-level decision-making by identifying bestsellers, underperforming items, and margin drivers.

---

### 📍 5. Location Analysis Dashboard
Analyzes geographical sales distribution and profitability trends.

**Key Metrics & Visuals:**
- Top 3 Profitable Location Types  
- Top 3 Profitable Cities  
- Top 5 States by Population  
- Interactive Map Visualization: *Sales Details by State*  

**Business Insight:**  
Identifies top-performing markets and provides regional insights for expansion and strategy planning.

---

### 🧑‍💼 6. Sales Team Analysis Dashboard
Evaluates sales team and individual performance metrics.

**Key Metrics & Visuals:**
- Revenue and Profit by Salesperson  
- Revenue and Profit per Salesperson  
- Total Revenue by Sales Team  
- Gross Profit by Sales Team  
- Total Orders and Average Discount by Sales Team  

**Business Insight:**  
Monitors sales productivity, highlights top-performing employees, and identifies discount effectiveness.

---

### 📅 7. Year Analysis Dashboard
Provides a time-series view of business performance over multiple years.

**Key Metrics & Visuals:**
- Revenue by Month and Year  
- % Month-to-Month Growth  
- % Year-to-Year Growth  
- Revenue & Profit by Quarter  
- Revenue by Weekday and Month  

**Business Insight:**  
Reveals seasonal trends, growth patterns, and profitability variations across time periods.

---

## ⚙️ Technical Implementation

### 🧮 Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)** for calculated columns and measures  
- **Power Query Editor** for data transformation and cleaning  
- **Data Modeling** with one-to-many relationships between fact and dimension tables  
- **Slicers and Drill-through Filters** for user interactivity  
- **Bookmarks and Buttons** for page navigation  

### 🧠 DAX Measures Used
- **Total Revenue = SUM(Sales[Revenue])**  
- **Gross Profit = SUM(Sales[Revenue]) - SUM(Sales[COGS])**  
- **Profit Margin % = [Gross Profit] / [Revenue]**  
- **Month-over-Month Growth = (Current Month - Previous Month) / Previous Month**  
- **Year-over-Year Growth = (Current Year - Previous Year) / Previous Year**  

---

## 🧠 Business Outcomes & Insights
- Improved **decision-making efficiency** through unified financial visibility.  
- Quick identification of **profitability drivers** by product, region, and salesperson.  
- Enhanced **customer retention strategies** through behavior and recency analysis.  
- Streamlined **shipping and delivery process** tracking for operational optimization.  
- Demonstrated ability to design and develop **interactive BI systems** aligned with SQLBI’s 15 Dashboard Design Rules.

---

## 📂 Project Structure
```
📁 Advanced-Financial-Analytics-Dashboard/
│
├── 📊 PowerBI_File.pbix
├── 🖼️ images/
│   ├── homepage.png
│   ├── customer_analysis.png
│   ├── transaction_analysis.png
│   ├── product_analysis.png
│   ├── location_analysis.png
│   ├── sales_team_analysis.png
│   └── year_analysis.png
└── README.md
```

---

## 🚀 How to Use
1. Download or clone this repository.  
2. Open the `.pbix` file in **Microsoft Power BI Desktop**.  
3. Use the **Home Page** navigation buttons to explore dashboards.  
4. Apply filters like **Year, Sales Team, Channel, and Region** for customized analysis.

---

## 💡 Design Guidelines Followed
- **Minimalism:** Kept dashboards clean, focusing on critical KPIs.  
- **Consistency:** Uniform color palette and typography across all pages.  
- **Readability:** Simplified number formatting and chart legends.  
- **Interactivity:** Added buttons, slicers, and bookmarks for dynamic exploration.  
- **Performance:** Optimized data model relationships and measures for faster load times.

---

## 📚 Learning Outcomes
Through this project, the following Power BI skills were strengthened:
- Data cleaning and ETL in Power Query  
- Building DAX measures for profit, growth, and ranking  
- Designing multi-page interactive dashboards  
- Applying UX/UI design principles in analytics  
- Publishing dashboards for portfolio or stakeholder presentation   

---

⭐ **If you found this project valuable, please star the repository and share it with fellow Power BI learners!**
