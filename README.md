# 🛍️ Customer Shopping Behavior 
 
A full-stack analytics project using **PostgreSQL**, **Excel**, **Jupyter Notebook**, and **Power BI** to explore customer shopping patterns across 3,900 records and 18 features.

## 🐘 1. PostgreSQL
CREATE TABLE schema matching all 18 columns, a COPY import command, and 8 ready-to-run analytical queries covering revenue by category, top states, discount impact, age segmentation, and subscriber analysis.

## 📊 2. Excel
Step-by-step workflow: cleaning the 37 null Review Rating values, 5 recommended pivot table setups, key formulas (AVERAGEIF, SUMIF, COUNTIF), and chart suggestions.

## 🐍 3. Jupyter Notebook
12 cells covering the full pipeline: load → clean → EDA → 8 visualizations (bar, histogram, pie, boxplot, heatmap, correlation matrix) using pandas, matplotlib, seaborn, and plotly.

## 📈 4. Power BI Dashboard

1. Open Power BI Desktop → **Get Data → Excel Workbook**
2. Select `customer_shopping_behavior.xlsx` → check `customer_shopping_behavior` sheet → **Load**
3. Open **Power Query Editor** to clean data:
   - Replace nulls in `Review Rating`: Transform → Replace Values → `null` → `3.75` (or use median)
   - Change `Purchase Amount (USD)` to **Whole Number** type
   - Change `Review Rating` to **Decimal Number** type
4. Dashboard result.

# Sample Dashboard

![image_alt](https://github.com/vaishnavi-selvamraj/Customer_behavior/blob/main/Screenshot%20(68).png?raw=true)

## ✅ Overview
 
- [ ] Export `.xlsx` to `.csv` for PostgreSQL import
- [ ] Run `CREATE TABLE` and `COPY` commands in PostgreSQL
- [ ] Build pivot tables and charts in Excel
- [ ] Run Jupyter notebook end-to-end; check all plots render
- [ ] Connect Power BI to Excel, replace nulls in Power Query
- [ ] Create DAX measures before building visuals
- [ ] Publish Power BI report to workspace and share link
