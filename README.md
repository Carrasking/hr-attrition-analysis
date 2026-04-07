# 🏢 HR Analytics — Employee Attrition Analysis

> **Can we predict who's about to quit — and why?**  
> This project analyzes employee attrition data using Python and SQL to identify the key drivers of turnover and deliver actionable retention recommendations.

---

## 📌 Business Problem

High employee turnover is expensive. Replacing a single employee costs an estimated **1.5× their annual salary** in recruiting, onboarding, and lost productivity. This analysis helps HR leadership answer three critical questions:

1. **Who is leaving?** — Which profiles are most at risk?
2. **Why are they leaving?** — What are the key drivers?
3. **What can we do?** — Data-backed recommendations to reduce attrition.

---

## 🔍 Key Findings

| Finding | Detail |
|---------|--------|
| 🔴 Overtime is the #1 driver | Employees working OT leave at **37.4%** vs 18.1% — a 2× risk |
| 🔴 First-year employees are most vulnerable | 0–1 year tenure shows **~42% attrition** — an onboarding red flag |
| 🟡 HR department is highest-risk | **29.3% attrition** — the team responsible for retention is itself churning |
| 🟡 Income gap is significant | Employees who left earned **$901/month less** on average |
| 🟡 Low satisfaction + poor WLB = 50%+ churn | The combination is far more predictive than either factor alone |

---

## 💡 Recommendations

1. **Audit overtime** — identify chronically overloaded teams and redistribute workload
2. **Strengthen onboarding** — 30/60/90-day check-ins for all new hires
3. **Review comp for high-risk roles** — HR Reps and Sales Reps show highest attrition + lowest pay
4. **Track satisfaction + WLB together** — quarterly pulse surveys on both dimensions
5. **Prioritize the HR department** — losing HR staff undermines all other retention efforts

---

## 📊 Visualizations

| Figure | Description |
|--------|-------------|
| Fig 1 | Attrition rate by department |
| Fig 2 | Overtime vs attrition — distribution and rate comparison |
| Fig 3 | Monthly income: stayed vs left (KDE + box plot) |
| Fig 4 | Heatmap: Job Satisfaction × Work-Life Balance → attrition rate |
| Fig 5 | Attrition rate by tenure band (with employee count overlay) |

---

## 🛠️ Tools & Stack

| Tool | Purpose |
|------|---------|
| **Python 3** | Core analysis language |
| **Pandas** | Data manipulation and aggregation |
| **Matplotlib + Seaborn** | Data visualization |
| **SQLite + SQL** | In-notebook database queries |
| **Jupyter Notebook** | Analysis environment |

---

## 📂 Project Structure

```
hr-attrition-analysis/
│
├── HR_Attrition_Analysis.ipynb   ← Main analysis notebook
├── README.md                      ← This file
```

---

## 📈 Estimated Business Impact

Assuming a conservative replacement cost of 1.5× annual salary:
- Current attrition: ~346 employees/year
- If attrition reduced by **30%** → ~103 fewer departures
- Estimated annual savings: **$3.7M+** (avg salary $80K)

---

## 🗃️ Dataset

This project uses a **synthetic dataset** (1,470 employees) modeled after the publicly available [IBM HR Analytics Employee Attrition dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) on Kaggle. The synthetic version is fully self-contained — no download required.

---

## 👤 Author

**Jorge Carrasco**  
Business Insights & Analytics — Humber Polytechnic  
[LinkedIn](https://www.linkedin.com/in/jcarrascof) · [GitHub](https://github.com/Carrasking)

---

*Tags: `python` `pandas` `sql` `sqlite` `data-analysis` `hr-analytics` `attrition` `matplotlib` `seaborn` `jupyter-notebook` `eda` `business-intelligence`*
