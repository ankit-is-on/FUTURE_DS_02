# FUTURE_DS_02 — Customer Retention & Churn Analysis

> **Future Interns — Data Science & Analytics Internship | Task 2**

---

## 🚀 Project Overview

This project analyzes customer churn behavior in a subscription-based business using Python and interactive visualizations.

**Goals:**
- Analyze churn patterns across plans, regions, tenure, and payment methods
- Identify key retention drivers and churn reasons
- Perform cohort analysis on monthly signup groups
- Generate actionable business recommendations
- Build an interactive analytics dashboard

---

## 📂 Repository Structure

```
FUTURE_DS_02/
│
├── dataset/
│   └── Churn_Analysis_Dataset.xlsx
│
├── notebook/
│   └── Analysis.ipynb          ← EDA + 14 charts
│
├── dashboard/
│   └── Dashboard.ipynb         ← Interactive Plotly dashboard
│
├── images/
│   └── chart1 to chart14.png   ← All saved visualizations
│
├── report/
│   └── Task_Report.pdf         ← PDF summary report
│
├── insights/
│   └── key_insights.md         ← Key findings & recommendations
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

**File:** `Churn_Analysis_Dataset.xlsx`  
**Rows:** 1,000 customers | **Columns:** 14

| Column | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Age | Customer age |
| Region | East / West / North / South |
| Plan | Basic / Standard / Premium |
| Tenure_Months | How long customer has been subscribed |
| Monthly_Charge | Monthly billing amount (₹) |
| Total_Charges | Cumulative billing amount (₹) |
| Num_Products | Number of products subscribed |
| Support_Calls | Number of support calls made |
| Payment_Method | Debit Card / Credit Card / UPI / Net Banking |
| Join_Date | Date of first subscription |
| Churned | 0 = Retained, 1 = Churned |
| Churn_Reason | Reason for churning (if churned) |
| Cohort_Month | Month of joining (YYYY-MM) |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Core language |
| Pandas | Data cleaning & analysis |
| NumPy | Numerical operations |
| Matplotlib | Static visualizations |
| Seaborn | Statistical plots |
| Plotly | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## ▶️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/FUTURE_DS_02.git
cd FUTURE_DS_02

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open notebooks
jupyter notebook
```

Open `notebook/Analysis.ipynb` for EDA and charts.  
Open `dashboard/Dashboard.ipynb` for the interactive Plotly dashboard.

---

## 💡 Key Insights

| # | Insight |
|---|---|
| 1 | **Basic plan** churn rate is **20.9%** — nearly 3× higher than Premium (7.3%) |
| 2 | **First 24 months** are highest-risk — 20–23% churn vs 7–10% after month 25 |
| 3 | **Price-related reasons** drive **45% of all churn** (better price + financial constraints) |
| 4 | **East region** has the highest churn at **18.3%** vs South at 10.8% |
| 5 | **Churned customers** paid only ₹472/mo on average vs ₹594 for retained — lower-tier users are underserved |
| 6 | **October 2023 cohort** has the highest churn rate at **21.9%** |

---

## 🚀 Recommendations

1. **Early lifecycle intervention** — Automated check-ins for months 1–24
2. **Basic plan value upgrade** — Mid-tier benefits or loyalty discounts after 12 months
3. **Competitive price response** — Win-back program for price-sensitive churners
4. **East region focus** — Dedicated CX audit and regional retention effort
5. **Flexible payment options** — EMI or hardship deferrals for financial constraint cases
6. **Feature gap roadmap** — Quarterly product surveys for lower-tier plan users

---

## 📈 Charts Included (14 total)

1. Overall Churn Distribution
2. Churn by Plan Type
3. Churn by Tenure Group
4. Churn Reasons Breakdown
5. Churn by Region
6. Churn by Payment Method
7. Monthly Charges Distribution
8. Tenure Distribution
9. Age Group Analysis
10. Support Calls vs Churn
11. Monthly Cohort Analysis
12. Correlation Heatmap
13. Total Charges vs Churn
14. Number of Products vs Churn

---

## 👩‍💻 Author

**Ankit**  

🎓 B.Tech in Artificial Intelligence

🏫Delhi Skill and Entrepreneurship University (DSEU)

---

## ⭐ Acknowledgement

This project was completed as part of the **Future Interns Data Science & Analytics Internship Program**.  

Special thanks to Future Interns for providing practical industry-oriented learning opportunities.
