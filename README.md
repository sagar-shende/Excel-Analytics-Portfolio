<div align="center">

# 📊 Excel Data Analysis — Basic to Advanced

<img src="https://img.shields.io/badge/Microsoft_Excel-Advanced-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Datasets-4_Projects-0078D4?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Domains-Finance_|_Films_|_Ecommerce_|_Maritime-6C3483?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-22C55E?style=for-the-badge"/>

<br/>

> 🎯 A collection of **4 real-world Excel analysis projects** covering
> data cleaning, advanced formulas, pivot tables, and interactive dashboards
> across **Entertainment**, **Finance**, **E-Commerce**, and **Historical** domains.

<br/>

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Projects at a Glance](#-projects-at-a-glance)
- [Project 1 — IMDB Data Analysis](#-project-1--imdb-data-analysis)
- [Project 2 — Loan Approval Analysis](#-project-2--loan-approval-analysis)
- [Project 3 — Ecommerce Churn Analysis](#-project-3--ecommerce-churn-analysis)
- [Project 4 — Titanic Survival Analysis](#-project-4--titanic-survival-analysis)
- [Skills Demonstrated](#-skills-demonstrated)
- [Excel Features Used](#-excel-features-used)
- [Project Structure](#-project-structure)
- [How to Open](#-how-to-open)
- [Author](#-author)

---

## 🔍 Overview

This repository showcases a **progression from basic to advanced Excel skills** through hands-on analysis of four industry-relevant datasets. Each project tackles a unique business problem — from entertainment analytics and credit risk, to customer retention strategy and historical survival modeling.

**What's covered:**
- 🧹 Raw data cleaning and transformation pipelines
- 🔢 Advanced formula engineering (VLOOKUP, XLOOKUP, nested IFs)
- 📊 Pivot Table design and dynamic summarization
- 📈 Chart storytelling — choosing the right visual for the right insight
- 📋 Dashboard creation with KPIs, slicers, and conditional formatting

---

## 🗂️ Projects at a Glance

| # | Project | Domain | Records | Complexity | Highlight |
|---|---------|--------|---------|------------|-----------|
| 1 | 🎬 IMDB Data Analysis | Entertainment | 1,000+ movies | ⭐⭐⭐ | Genre & Rating Trend Dashboard |
| 2 | 🏦 Loan Approval Analysis | Finance | 600+ applications | ⭐⭐⭐⭐ | Credit Risk Scoring with VLOOKUP |
| 3 | 🛒 Ecommerce Churn Analysis | E-Commerce | 5,000+ customers | ⭐⭐⭐⭐⭐ | Churn Prediction Dashboard |
| 4 | 🚢 Titanic Survival Analysis | Historical / Social | 891 passengers | ⭐⭐⭐⭐ | Survival Rate Dashboard by Class & Gender |

---

## 🎬 Project 1 — IMDB Data Analysis

**File:** `imdb_data_analysis.xlsx`

### Objective
Uncover patterns in movie ratings, genres, and release trends to understand what makes a film commercially and critically successful.

### Key Questions Answered
- Which genres consistently score the highest ratings?
- How have average ratings changed year over year?
- Which directors produce the most top-rated films?
- What is the correlation between votes and ratings?

### Techniques Used
```
✅ Data Cleaning       — Removed nulls, standardized genre names
✅ Pivot Tables        — Ratings by Genre, Director, Year
✅ Sorting & Ranking   — Top 10 movies by rating and votes
✅ Bar & Line Charts   — Genre performance, yearly trends
✅ Conditional Format  — Highlighted top-rated movies (green) vs low (red)
```

### Key Insights
```
🏆 Drama & Documentary genres have highest avg ratings (7.8+)
📅 Rating quality peaked around 2010–2015 period
🎬 Top directors appear consistently in 8.0+ rated films
📊 High vote count strongly correlates with higher ratings
```

---

## 🏦 Project 2 — Loan Approval Analysis

**File:** `loan_approval_analysis.xlsx`

### Objective
Analyze loan application data to identify the key factors that determine approval decisions and build a risk classification framework.

### Key Questions Answered
- What income level has the highest approval rate?
- Does credit score alone determine loan approval?
- Which applicant profiles are highest risk?
- How does loan amount affect approval probability?

### Techniques Used
```
✅ VLOOKUP / XLOOKUP   — Match applicant risk tier to approval rules
✅ Nested IF Formulas   — Multi-condition approval logic
✅ Conditional Format   — Red/Yellow/Green risk banding
✅ Pivot Tables         — Approval rate by income bracket, credit score
✅ Data Validation      — Dropdown lists for risk category input
✅ Percentage Charts    — Approval vs rejection breakdown
```

### Key Insights
```
💳 Credit Score > 700 has 85%+ approval rate
💰 Income ₹50K+ with low DTI ratio = highest approval probability
⚠️  Self-employed applicants show 30% higher rejection rate
📊 Loan-to-Income ratio is the strongest approval predictor
```

---

## 🛒 Project 3 — Ecommerce Churn Analysis

**File:** `ecommerce_churn_analysis.xlsx`

### Objective
Identify customers at risk of churning and uncover the behavioral patterns and service factors that drive customer attrition in an ecommerce platform.

### Key Questions Answered
- What is the overall churn rate and trend?
- Which customer segments churn the most?
- What is the impact of delivery issues on churn?
- Which product categories have highest churn-linked complaints?

### Techniques Used
```
✅ Data Cleaning        — Deduplication, null handling, type correction
✅ Churn Flagging       — IF + AND formula logic for churn classification
✅ Pivot Tables         — Churn by segment, city, category, complaint type
✅ Donut & Bar Charts   — Churn rate visualization by dimension
✅ KPI Dashboard        — Churn %, Retained Customers, At-Risk count
✅ Slicers              — Interactive filtering by region, category, tenure
✅ Sparklines           — Monthly churn trend inline in summary table
```

### Key Insights
```
📉 Overall churn rate: ~26% of the customer base
🚚 Delivery delay complaints linked to 40%+ of churned customers
📦 Electronics & Fashion categories show highest churn correlation
👤 Customers with tenure < 6 months are 3x more likely to churn
🌆 Tier-2 cities show significantly higher churn than metros
```

---

## 🚢 Project 4 — Titanic Survival Analysis

**File:** `titanic_survival_analysis.xlsx`

### Objective
Analyze the Titanic passenger dataset to identify the key demographic and socioeconomic factors that influenced survival outcomes during the 1912 disaster.

### Key Questions Answered
- What was the overall survival rate across passengers?
- Did passenger class (1st / 2nd / 3rd) significantly affect survival?
- How did gender impact survival probability?
- Which age groups had the highest and lowest survival rates?
- Did embarkation port correlate with survival chances?

### Techniques Used
```
✅ Data Cleaning        — Handled missing Age, Cabin & Embarked values
✅ Derived Columns      — Age groups (Child / Adult / Senior) using nested IF
✅ COUNTIF / AVERAGEIF  — Survival rates by class, gender, age group
✅ Pivot Tables         — Survival breakdown by Pclass, Sex, Embarked
✅ Stacked Bar Charts   — Survived vs Not Survived by category
✅ Conditional Format   — Color-coded survival rate heatmap
✅ KPI Dashboard        — Total Passengers, Survivors, Survival %, by segment
```

### Key Insights
```
🚢 Overall survival rate: ~38% of 891 passengers
👩 Female survival rate (~74%) was nearly 3x higher than male (~19%)
🥇 1st class passengers had 63% survival vs only 24% in 3rd class
👶 Children (Age < 12) had highest survival rate across all groups
⚓ Passengers who embarked from Cherbourg had the highest survival rate
💡 Class + Gender combined = strongest predictor of survival outcome
```

---

## 🛠️ Skills Demonstrated

| Category | Skills | Used In |
|---|---|---|
| 🧹 **Data Preparation** | Cleaning, Deduplication, Type Formatting, Null Handling | All Projects |
| 🔢 **Formulas** | VLOOKUP, XLOOKUP, IF, AND, OR, COUNTIF, SUMIF, AVERAGEIF | P1, P2, P3, P4 |
| 📊 **Pivot Tables** | Multi-dimension summarization, Calculated Fields, Grouping | All Projects |
| 📈 **Charts** | Bar, Line, Donut, Stacked Bar, Clustered Column, Sparklines | All Projects |
| 🎨 **Formatting** | Conditional Formatting (rules-based), Data Bars, Icon Sets | P2, P3, P4 |
| 📋 **Dashboards** | KPI Cards, Slicers, Interactive Filters, Layout Design | P3, P4 |
| ✅ **Data Validation** | Dropdowns, Input Messages, Error Alerts | P2 |

---

## ⚡ Excel Features Used

```
📌 Pivot Tables          → Dynamic summaries & cross-tabulation
📌 VLOOKUP / XLOOKUP     → Cross-sheet data matching
📌 Nested IF Statements  → Multi-condition business logic
📌 COUNTIF / SUMIF       → Conditional aggregation
📌 Conditional Formatting → Visual risk banding & heat maps
📌 Data Validation       → Input control & dropdowns
📌 Slicers               → One-click dashboard filtering
📌 Sparklines            → Inline trend indicators
📌 Named Ranges          → Clean, readable formula references
📌 Charts & Graphs       → Bar, Line, Donut, Stacked Bar, Clustered Column
```

---

## 📁 Project Structure

```
excel-data-analysis/
│
├── 📊 imdb_data_analysis.xlsx           # Project 1 — Entertainment
│   ├── Sheet: Raw_Data
│   ├── Sheet: Cleaned_Data
│   ├── Sheet: Pivot_Analysis
│   └── Sheet: Dashboard
│
├── 📊 loan_approval_analysis.xlsx       # Project 2 — Finance
│   ├── Sheet: Applications
│   ├── Sheet: Risk_Scoring
│   ├── Sheet: Pivot_Summary
│   └── Sheet: Approval_Dashboard
│
├── 📊 ecommerce_churn_analysis.xlsx     # Project 3 — E-Commerce
│   ├── Sheet: Customer_Data
│   ├── Sheet: Cleaned_Data
│   ├── Sheet: Churn_Flags
│   ├── Sheet: Pivot_Analysis
│   └── Sheet: Churn_Dashboard
│
├── 📊 titanic_survival_analysis.xlsx    # Project 4 — Historical
│   ├── Sheet: Raw_Data
│   ├── Sheet: Cleaned_Data
│   ├── Sheet: Pivot_Analysis
│   └── Sheet: Survival_Dashboard
│
└── 📝 README.md
```

---

## 🚀 How to Open

### Requirements
- **Microsoft Excel 2016+** or **Microsoft 365** *(recommended)*
- Google Sheets *(basic features only — some advanced formatting may vary)*

### Steps
```
1. Download the .xlsx file for the project you want to explore
2. Open with Microsoft Excel
3. Enable editing if prompted (Required for slicers & pivots)
4. Navigate using the Sheet tabs at the bottom
5. Use slicers / dropdowns on Dashboard sheet to interact
```

> 💡 **Tip:** For the best experience with dashboards and slicers, use **Microsoft 365 Excel** or **Excel 2019+**

---

## 👤 Author

<div align="center">

**Sagar Kishor Shende**
*Data Analytics & AI Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-sagar--shende-181717?style=for-the-badge&logo=github)](https://github.com/sagar-shende)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sagar_Shende-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sagarshende-ai)
[![Email](https://img.shields.io/badge/Email-sagarshende0608@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sagarshende0608@gmail.com)

</div>

---

<div align="center">

**⭐ If this helped you learn Excel analytics, give it a star!**

*Built with 💚 using Microsoft Excel · Pivot Tables · DAX-style Logic · Data Storytelling*

</div>
