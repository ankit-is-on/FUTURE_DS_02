# Key Insights — Customer Churn Analysis
**Future Interns | Data Science & Analytics | Task 2**

---

## Dataset Overview
| Metric | Value |
|---|---|
| Total Customers | 1,000 |
| Churned Customers | 143 (14.3%) |
| Retained Customers | 857 (85.7%) |
| Avg Tenure — Active | 32.1 months |
| Avg Tenure — Churned | 19.4 months |
| Avg Monthly Charge — Active | ₹594 |
| Avg Monthly Charge — Churned | ₹472 |

---

## Insight 1 — Basic Plan Has 3× Higher Churn Than Premium
| Plan | Customers | Churned | Churn Rate |
|---|---|---|---|
| Basic | 401 | 84 | **20.9%** |
| Standard | 351 | 41 | 11.7% |
| Premium | 248 | 18 | **7.3%** |

→ Basic plan subscribers churn at nearly 3× the rate of Premium users. The plan likely lacks sufficient perceived value. Upsell campaigns or feature enhancements for Basic users are needed urgently.

---

## Insight 2 — First 24 Months Are the Highest-Risk Window
| Tenure Group | Churn Rate |
|---|---|
| 0–12 Months | **23.3%** |
| 13–24 Months | **20.8%** |
| 25–36 Months | 7.8% |
| 37–60 Months | 10.3% |

→ Churn drops sharply after month 24. Early-lifecycle customers are most vulnerable. A structured onboarding program and 6-month check-in campaigns could significantly reduce this drop-off.

---

## Insight 3 — Price Is the #1 Churn Driver (45% of All Churn)
| Churn Reason | Customers | Share |
|---|---|---|
| Better Price Elsewhere | 37 | 25.9% |
| Financial Constraints | 28 | 19.6% |
| Poor Customer Service | 25 | 17.5% |
| Lack of Features | 22 | 15.4% |
| Moved Away | 16 | 11.2% |
| Switched to Competitor | 15 | 10.5% |

→ Price-related reasons account for 45.5% of total churn. This suggests a competitive pricing gap, not a product quality issue. Targeted discounts and flexible billing can address this directly.

---

## Insight 4 — East Region Leads in Churn
| Region | Churn Rate |
|---|---|
| East | **18.3%** |
| North | 15.2% |
| West | 12.8% |
| South | 10.8% |

→ East region churn is 69% higher than South. Possible causes: stronger local competition, weaker customer support, or demographic differences. Needs dedicated investigation.

---

## Insight 5 — Churned Customers Were Lower-Paying
- Avg monthly charge of churned customers: **₹472**
- Avg monthly charge of retained customers: **₹594**

→ Churned customers were on cheaper plans (Basic/Standard), not overpaying. This rules out "price shock" as the cause — it points to underserved lower-tier customers who need more value for their spend.

---

## Insight 6 — October 2023 Cohort Has Highest Churn (21.9%)
Monthly cohort churn rates ranged from 5.5% (Dec-23) to 21.9% (Oct-23). The October cohort significantly underperforms.

→ Suggests a possible onboarding issue, a product outage, or a poor acquisition campaign during October. A retroactive review of that cohort's experience is recommended.

---

## Business Recommendations

1. **Early Lifecycle Intervention** — Deploy automated check-ins for customers in months 1–24. Target users with high support calls and fewer products.
2. **Basic Plan Value Upgrade** — Introduce mid-tier benefits or loyalty discounts after 12 months to reduce 20.9% Basic plan churn.
3. **Competitive Price Response** — Create a win-back program for customers citing "Better Price Elsewhere." Offer price-match or flexible billing.
4. **East Region Focus** — Audit CX quality in the East region. Consider dedicated regional success resources.
5. **Flexible Payment Options** — Offer EMI or hardship deferrals to reduce "Financial Constraints" churn, especially for UPI and Debit Card users.
6. **Feature Gap Roadmap** — Survey Basic and Standard users quarterly to build a prioritized feature list addressing the 15.4% who left due to "Lack of Features."
