# G-3-DVA-Capstone-Project

# Sectoral Data Analytics: Mutual Fund Market Intelligence

## Project Overview

This project is a 2-week industry simulation designed to convert a raw, "messy" mutual fund dataset into actionable business intelligence. Operating as analytics consultants, our team is tasked with data engineering, performing deep-dive analysis using pivot tables, and designing an interactive dashboard to drive investment decisions.

---

## The Team & Roles

This project is executed by a specialized team of 6 members as per the DVA Capstone guidelines:

- **Ranajeet Roy** | **Project Lead**  
  Responsible for timeline management, submission compliance, and the Day 3 "Data Approval" gate.

- **Yatin Singh** | **Strategy Lead**  
  Oversees the business logic, framing the core analytical questions, and final recommendations.

- **Pratham Malhotra** | **Data Lead**  
  Owns the data cleaning, standardization, and the creation of the Data Dictionary.

- **Ved Pawar** | **Dashboard Lead**  
  Focuses on UI/UX, interactivity, and the visual clarity of the final dashboard.

- **Abhijeet Kumar** | **Analytics Lead**  
  Responsible for KPI construction, Pivot Table logic, and uncovering advanced insights.

- **Pushkar Jain** | **PPT & Quality Lead**  
  Ensures the professional storytelling of the 10-slide deck and overall project quality.

---

## Dataset Focus

The analysis utilizes the `mutual_fund_data.csv` dataset, which includes:

- **Scheme Categorization**: Equity, Debt, and Hybrid schemes across various AMCs (e.g., Aditya Birla Sun Life, DSP, HDFC).
- **Performance Metrics**: Net Asset Value (NAV) and the Latest NAV Date.
- **Financials**: Average Assets Under Management (AUM) in Crores and investment windows (Launch/Closure dates).
- **Identifiers**: Unique Scheme Codes and ISIN numbers for Growth and IDCW options.

---

## Implementation Workflow

### Phase 1: Data Engineering (Week 1)

- **Cleaning**: Handling null values in `NAV` and `Average_AUM_Cr` columns.
- **Standardization**: Converting `Launch_Date` and `Latest_NAV_Date` into uniform date formats for time-series analysis.
- **Data Dictionary**: Developing a comprehensive guide mapping every variable in the mutual fund dataset.

### Phase 2: Analytics & Dashboarding (Week 2)

- **Pivot Table Engine**: Used to segment AUM and NAV performance by `Scheme_Category` and `AMC`.
- **KPI Development**: Identifying top-performing schemes and asset concentration trends.
- **Interactive Dashboard**: A user-friendly tool built to answer specific business questions and support data-driven decisions.
