# Excel-Sales-Analytics
# AtliQ Sales & Finance Analytics (Excel + Power Query)

## 📌 Overview
This project showcases an **end-to-end Sales & Finance Analytics solution** built in Excel using **Power Query + PivotTables**.  
It covers Sales Performance, Target Tracking, Net Sales by Customer, and Profitability Analysis (P&L) across time and markets.  

The demo is based on AtliQ Hardware’s sales & finance dataset (sample/anonymized).  

---

## 🛠️ Tools Used
- Microsoft Excel (Power Query + PivotTables)
- Data Modeling with Relationships
- Basic calculations (Net Sales, COGS, Gross Margin, Margin %)
- Visual Dashboards for storytelling

---

## 📊 Dashboards & Key Insights

### 1. Performance vs Target
- Tracks sales growth (2019–2021) vs targets across 20+ countries.
- **India** achieved $161M in 2021 (–5.9% vs target).
- **USA** at $87M (–11.7% vs target).
- Several European countries had double-digit shortfalls.

### 2. Net Sales by Customer
- Customer-level growth analysis (2019–2021).
- **Chiptec**: +722%, **Integration Stores**: +887%.
- **Amazon** +219%, **Flipkart** +231%.
- Retailers like **BestBuy** (+356%) and **Costco** (+337%) also expanded strongly.

### 3. P&L by Month
- Full monthly view of Net Sales, COGS, and Gross Margin.
- Net Sales: **$87M (2019) → $598M (2021)**, ~6.8× growth.
- GM% fell from ~41% (2019) to ~36% (2021).

### 4. P&L by Market
- Market-level profitability snapshot for 2021.
- **India**: $161M Net Sales, GM% = 32%.
- **New Zealand**: GM% = 48.2% (highest margin).
- **Japan (46.5%)** and **UK (45.1%)** are strong performers.
- **Germany (26.2%)** and **Norway (29.5%)** show efficiency gaps.

---

## 🔄 Process (ETL + Modeling)
1. **Extract** – imported multi-year sales & finance data into Power Query.
2. **Transform** – cleaned, merged product/customer/target tables, built a Date table.
3. **Load** – loaded transformed tables into Excel Data Model.
4. **Analyze** – created PivotTables, KPI measures, and charts.
5. **Visualize** – built dashboards for Sales vs Target, Net Sales by Customer, and P&L views.

---

