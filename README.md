# 📊 Power BI Sales Analysis Project

## 📌 Overview
This project demonstrates data cleaning, modeling, calculated columns, DAX measures, quick measures, iterator functions, and time intelligence in Power BI.  
The goal was to analyze sales, costs, profits, returns, and customer details with both simple and advanced DAX functions.

---

## 🛠️ Data Preparation
- Loaded raw data files into Power BI.
- Changed data types for correct representation (dates, numbers, text).
- Removed blank rows and unnecessary fields.

---

## 🧮 Calculated Columns
1. Profit in Sales table (SalesAmount - Cost).  
2. Return Flag in Sales table to identify returned or not returned transactions.  
3. Customer Full Name in Customer table (First Name + Last Name).

---

## 📊 Measures
- Total Sales  
- Total Cost  
- Total Profit  
- Return Rate (% of items returned)  
- Average Sale per Transaction  

---

## ⚡ Quick Measures
- Year-over-Year Sales Growth %  
- Month-over-Month Sales Difference  

---

## 📂 Measure Table
- Created a dedicated **Measure Table** to organize all measures.  
- Grouped into folders for Sales, Profitability, Returns, and Time Intelligence.

---

## 🧾 Matrix Analysis
- Compared sales by region with and without filters using:  
  - **ALL()** – to remove filters and show all regions.  
  - **FILTER()** – to show only sales with profit above a threshold.  
  - **CALCULATE()** – to apply filter context dynamically.  

---

## 📚 DAX Functions Practice
- **Math & Statistics**: SUM, AVERAGE, MAX  
- **Counting**: COUNTX, DISTINCTCOUNT  
- **Conditional Logic**: IF, AND, OR, SWITCH  
- **Text Functions**: CONCATENATE, UPPER, LEFT  
- **Date Functions**: YEAR, MONTH, EOMONTH  

---

## 🔗 RELATED Function
- Used RELATED to bring fields from dimension tables into fact tables for analysis.

---

## ⏳ Time Intelligence
- **TOTALYTD()** – cumulative Year-to-Date sales.  
- **SAMEPERIODLASTYEAR()** – compare sales with the same period last year.  
- **DATESINPERIOD()** – analyze sales in rolling periods (e.g., last 90 days).  
- **DATESBETWEEN()** – custom range analysis (e.g., half-month sales).  
- **Running Total** – cumulative sales across months using CALCULATE + date functions.  

---

## 🔄 Iterator Functions
- **SUMX()** – calculated profit row by row and aggregated.  
- **AVERAGEX()** – calculated average profit per transaction.  
- **Other Iterators** – used in measures for margin % and customer-level analysis.  

---

## ✅ Summary
- Cleaned and prepared data model.  
- Built calculated columns for profit, return flags, and customer full names.  
- Created base measures, quick measures, iterator measures, and time intelligence metrics.  
- Practiced DAX functions across categories (math, text, date, logical).  
- Used Matrix visual for sales analysis across regions, months, and years.  
- Organized everything neatly into a dedicated Measure Table for clarity.  
