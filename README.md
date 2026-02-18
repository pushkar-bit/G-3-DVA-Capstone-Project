---

## 📌 Project Overview

This project is a **2-week industry-style analytics simulation** conducted as part of the **Data Visualization & Analytics (DVA) Capstone**. Acting as data consultants, our team transformed a large, unstructured mutual fund dataset into a **decision-support intelligence dashboard**.

The raw dataset contained **16,000+ mutual fund schemes** with inconsistent formatting, missing values, and mixed data types. The objective was to clean, structure, analyze, and visualize this data to enable **faster fund comparison, market insight discovery, and strategic investment analysis**.

The final output is an **interactive Google Sheets dashboard** that highlights:
- Asset concentration across AMCs
- Scheme accessibility for retail investors
- Category-wise fund dominance
- Market structure and maturity trends

---

## 👥 The Team & Roles

This project was executed by a structured 6-member team in alignment with DVA Capstone guidelines:

- **Ranajeet Roy** — *Project Lead*  
  Responsible for project coordination, timeline management, and data approval checkpoints.

- **Yatin Singh** — *Strategy Lead*  
  Framed business questions, analytical direction, and final recommendations.

- **Pratham Malhotra** — *Data Lead*  
  Owned data cleaning, standardization logic, and the Data Dictionary.

- **Ved Pawar** — *Dashboard Lead*  
  Designed dashboard layout, slicers, and visual hierarchy.

- **Abhijeet Kumar** — *Analytics Lead*  
  Developed KPIs, pivot table logic, and advanced insights.

- **Pushkar Jain** — *PPT & Quality Lead*  
  Ensured professional documentation, presentation quality, and insight clarity.

---

## 📊 Dataset Description

**Dataset Name:** India’s Ultimate Mutual Fund Dataset  
**File:** `mutual_fund_data.csv`  
**Records:** 16,319  
**Columns:** 16  

### Key Data Elements
- **Scheme Information:** Scheme Code, Scheme Name, Scheme Category, Scheme Type  
- **Financial Metrics:** Net Asset Value (NAV), Average AUM (₹ Crores)  
- **Investment Accessibility:** Minimum Investment Amount  
- **Time Attributes:** Launch Date, Closure Date, Latest NAV Date  
- **Identifiers:** ISIN (Growth / IDCW / Reinvestment)

---

## 📘 Data Dictionary (Key Columns)

| Column Name | Description |
|------------|-------------|
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

## 🧹 Data Cleaning Notes

All data cleaning was performed in **Google Sheets**.

### Key Cleaning Steps
- **Scheme_Min_Amt:**  
  Removed text-based values (e.g., “Rs. 5000 and multiples”), extracted numeric amounts, and standardized the column.

- **Missing Values:**  
  Identified null values in `Average_AUM_Cr` and excluded them from aggregate metrics to avoid skew.

- **Text Standardization:**  
  Cleaned and normalized AMC names, scheme categories, and scheme types using trimming and case formatting.

- **Date Standardization:**  
  Converted launch and NAV dates into proper date objects for time-based analysis.

- **Feature Engineering:**  
  Created derived fields such as *Fund Age Groups* and *NAV Buckets* for segmentation.

---

## 📈 Key Insights & Statistics

- **Market Concentration:**  
  The top 5 AMCs control over **40% of total recorded AUM**, indicating high concentration.

- **Asset Class Dominance:**  
  Equity schemes dominate the market by scheme count, reflecting strong retail interest.

- **Liquidity Preference:**  
  Over **90%** of schemes are open-ended, highlighting investor demand for flexibility.

- **Accessibility:**  
  Nearly **60%** of schemes allow entry with investments below ₹5,000.

- **Maturity Advantage:**  
  Legacy AMCs (15+ years old) exhibit significantly higher AUM stability than newer entrants.

---

## 📊 Dashboard Summary

The interactive dashboard is designed to answer the core business question:
> *Which AMCs and fund categories dominate the mutual fund market while remaining accessible to retail investors?*

### Dashboard Components
- **KPI Tiles:** Total AUM, Average NAV, Scheme Count, AMC Count
- **Bar Charts:** AMC-wise and Category-wise AUM distribution
- **Donut Charts:** Scheme category composition
- **Slicers:** AMC, Scheme Type, Category, Fund Age Group

The dashboard enables **multi-dimensional drill-down analysis** in real time.

---

## 🖼 Dataset Analysis Screenshots

Screenshots of:
- Cleaned dataset
- Pivot tables
- KPI calculations
- Final dashboard views  

are stored in the **`Dashboard/`** folder and referenced in the final presentation.

---

## 🚀 Conclusion

This capstone project demonstrates how structured data analytics can simplify a complex financial market. By converting a messy CSV into a clean, interactive intelligence system, the project delivers actionable insights into AMC dominance, investor accessibility, and market structure — supporting faster, data-driven decision-making.

---

## 📌 Future Scope

- Integration of historical NAV data for trend forecasting  
- Real-time API connections for live dashboards  
- Risk-adjusted performance metrics (volatility, Sharpe ratio)

---