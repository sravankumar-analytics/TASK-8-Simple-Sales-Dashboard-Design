# TASK-8-Simple-Sales-Dashboard-Design
Interactive Online Retail Sales &amp; Customer Insights Dashboard built in Power BI, showcasing sales trends, top products, and geographic distribution after extensive data cleaning.
# Online Retail Sales & Customer Insights Dashboard

## 📌 Overview
This project is an interactive Power BI dashboard designed to visualize sales and customer insights from an online retail dataset. The dashboard highlights trends, top products, and geographical distribution, providing a clear picture of business performance.

---

## 📊 Key Features
- **KPI Cards**: Displays Total Sales, Total Quantity, Total Customers, and Average Order Value.
- **Sales Trends**: Monthly total sales line chart to track performance over time.
- **Geographical Sales Map**: Shows sales distribution across countries.
- **Top Products**: Bar chart highlighting the highest-selling items.
- **Featured Product Display**: Showcases the top-selling product name.
- **Interactive Filters**: Country and Invoice Date filters for targeted analysis.

---

## 🧹 Data Cleaning Process
Before dashboard creation, the raw dataset underwent:
1. **Duplicate Removal** – Eliminated repeated invoice records.
2. **Missing Values Handling** – Removed rows with null customer IDs or descriptions.
3. **Data Type Corrections** – Ensured dates were in `datetime` format and numerical columns were correctly formatted.
4. **Negative Quantity & Returns Filtering** – Excluded refund/return transactions.
5. **Standardization** – Converted all product descriptions to proper case for consistency.
6. **Outlier Removal** – Removed extremely high transaction values that skewed results.

---

## 🛠️ Tools & Technologies
- **Power BI** – Dashboard creation & visualization
- **Excel** – Initial data cleaning & exploration
- **Dataset** – Online Retail Transaction Data (2010–2011)

---

## 📂 Repository Structure
