# 📊 Mutual Fund Analytics Dashboard  
**DVA Capstone Project**

---
## 🔗 Project Deliverable

The final interactive dashboard can be accessed here:

**📊 Mutual Fund Analytics Dashboard (Google Sheets)**  
https://docs.google.com/spreadsheets/d/16ElMb0FTYKnLBDf9hhPYoOXM3ZSa6DfOm477T5HaZGE/edit?usp=sharing

## 📌 Project Overview

This project is a **2-week industry-style analytics simulation** conducted as part of the **Data Visualization & Analytics (DVA) Capstone**.  
Acting as data consultants, our team transformed a large, unstructured mutual fund dataset into a **decision-support intelligence dashboard**.

The raw dataset contained **16,000+ mutual fund schemes** with inconsistent formatting, missing values, and mixed data types. The objective was to clean, structure, analyze, and visualize this data to enable:

- Faster fund comparison
- Market insight discovery
- Strategic investment analysis

The final output is an **interactive Google Sheets dashboard** that highlights:

- Asset concentration across AMCs
- Scheme accessibility for retail investors
- Category-wise fund dominance
- Market structure and maturity trends

---

## 👥 Team & Roles

This project was executed by a structured 6-member team:

| Member | Role | Responsibility |
|--------|------|---------------|
| Ranajeet Roy | Project Lead | Coordination, timeline management, data approvals | Data cleaning, standardization
| Yatin Singh | Strategy Lead | pivot table | Business questions, analytical direction, recommendations |
| Pratham Malhotra | Data Lead | Data cleaning, standardization, Data Dictionary |
| Ved Pawar | Dashboard Lead | Dashboard layout, slicers, visual design |
| Abhijeet Kumar | Analytics Lead | Data cleaning, standardization, KPIs, pivot logic and table, insights, Dashboard |
| Pushkar Jain | PPT & Quality Lead | Documentation, presentation quality |

---

## 📊 Dataset Description

**Dataset:** India’s Ultimate Mutual Fund Dataset  
**File:** `mutual_fund_data.csv`  
**Records:** 16,319  
**Columns:** 16  

### Key Data Elements

**Scheme Information**
- Scheme Code
- Scheme Name
- Scheme Category
- Scheme Type

**Financial Metrics**
- Net Asset Value (NAV)
- Average AUM (₹ Crores)

**Investment Accessibility**
- Minimum Investment Amount

**Time Attributes**
- Launch Date
- Closure Date
- Latest NAV Date

**Identifiers**
- ISIN (Growth / IDCW / Reinvestment)

---

## 📘 Data Dictionary (Key Columns)

| Column | Description |
|--------|-------------|
| Scheme_Code | Unique identifier for each scheme |
| Fund_House | Asset Management Company (AMC) |
| Scheme_Category | Equity, Debt, Hybrid, etc. |
| Scheme_Type | Open-ended / Closed-ended |
| Net_Asset_Value | Latest available NAV |
| Average_AUM_Cr | Average assets under management (₹ Crores) |
| Scheme_Min_Amt | Minimum investment amount |
| Launch_Date | Scheme inception date |
| ISIN | Unique security identifier |

---

## 🧹 Data Cleaning Process

All data cleaning was performed in **Google Sheets**.

### Key Steps

**1. Minimum Investment Cleaning**
- Removed text values like:  
  `Rs. 5000 and multiples`
- Extracted numeric amounts
- Standardized column values

**2. Missing Values**
- Identified null values in `Average_AUM_Cr`
- Excluded them from aggregate metrics

**3. Text Standardization**
- Cleaned AMC names
- Standardized scheme categories and types
- Applied trimming and case formatting

**4. Date Standardization**
- Converted launch and NAV dates into proper date formats

**5. Feature Engineering**
- Created:
  - Fund Age Groups
  - NAV Buckets

---

## 📈 Key Insights

- **Market Concentration**  
  Top 5 AMCs control **40%+ of total AUM**

- **Equity Dominance**  
  Equity schemes lead by scheme count

- **Liquidity Preference**  
  Over **90% of schemes are open-ended**

- **Retail Accessibility**  
  Nearly **60% of schemes** allow entry below ₹5,000

- **Maturity Advantage**  
  AMCs older than 15 years show higher AUM stability

---

## 📊 Dashboard Overview

The dashboard answers the key business question:

> **Which AMCs and fund categories dominate the market while remaining accessible to retail investors?**

### Dashboard Components

**KPI Tiles**
- Lowest Minimum Investment
- Lowest Avg Of Nav
- Highest Avg Of Nav
- Highest COUNT of Scheme_Code

**Charts**
- AMC vs/s AVERAGE of Average_AUM_Cr, AVERAGE of NAV, AVERAGE of Scheme_Min_Amt
- Scheme_Type vs COUNT of Scheme_Code
- Fund_Age (yrs) vs COUNT of Scheme_Code
- Scheme_Catagory_Type vs/s MEDIAN of Average_AUM_Cr, AVERAGE of NAV, AVERAGE of Scheme_Min_Amt
- Scheme_Min_Amt vs/s COUNT of Scheme_Code, AVERAGE of NAV, MEDIAN of Average_AUM_Cr

**Filters (Slicers)**
- AMC
- Scheme Type
- Scheme_Category_Type
- Sheme_Min_Amt
- Fund Age

The dashboard enables **real-time multi-dimensional analysis**.

---

## 🚀 Conclusion

This project demonstrates how structured data analytics can simplify a complex financial market.

By converting a messy CSV into a clean, interactive intelligence system, the project delivers actionable insights into:

- AMC dominance
- Investor accessibility
- Market structure

This enables **faster, data-driven decision-making**.

---

## 🔮 Future Scope

- Historical NAV trend forecasting
- Real-time API-based dashboards
- Risk-adjusted performance metrics  
  (volatility, Sharpe ratio)
