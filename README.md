# Customer Retention & Churn Analysis: Telco Dataset

## 📊 Project Overview

A comprehensive customer retention analysis on **7,043 telecom customers** using R and cohort analysis techniques. This project identifies churn patterns, retention drivers, and actionable recommendations to reduce customer churn.

## 🔍 Key Findings

### The Problem
- **26.5%** overall churn rate
- **52.94%** of churn happens in first 6 months
- **58.35%** churn rate for brand new customers (<3 months)

### The Insight
Once customers survive to month 24, churn stabilizes at **14.29%**. 
The first 90 days determine customer lifetime value.

### The Opportunity
A focused 30-day onboarding program could reduce early churn by **25-35%**, 
saving 260+ customers annually (~$39,325 in additional revenue).

## 📈 Analysis Breakdown

### 1. Tenure & Lifetime Analysis
- Customer tenure distribution by churn status
- Early churn (≤6 months): **52.94%**
- Long-term churn (>24 months): **14.04%**

### 2. Cohort Analysis & Retention Curves ⭐
- Tracked 4 customer cohorts by signup period (2020-01 through 2021-06)
- **2020-01 cohort:** Climbs to 95% retention by month 45
- **2021-06 cohort:** Stuck at 40-50% retention (4x worse performance)
- **Key Insight:** Mid-2021 operational change degraded retention

### 3. Churn Drivers Analysis
- Contract type, monthly charges, and tenure are strongest predictors
- Month-to-month contracts show highest churn risk
- Statistical tests validate findings

### 4. Customer Segmentation
- **Very High Risk (<3 months):** 58.35% churn | 862 customers
- **High Risk (3-12 months):** 41.09% churn | 1,207 customers
- **Moderate Risk (12-24 months):** 29.51% churn | 1,047 customers
- **Low Risk (24+ months):** 14.29% churn | 3,927 customers

## 💼 7 Actionable Recommendations

| Priority | Action | Impact | Timeline |
|----------|--------|--------|----------|
| CRITICAL | Redesign 30-day onboarding | -25-35% early churn | 45 days |
| CRITICAL | Investigate 2021 cohort degradation | Prevent recurrence | 14 days |
| HIGH | Contract upgrade incentive (15-20% discount) | 20-25% churn reduction | 30 days |
| HIGH | Automated check-ins (day 7, 14, 30) | 42% → 65% month-1 retention | 60 days |
| MEDIUM | Pricing tier reassessment | Stabilize high-value customers | 90 days |
| MEDIUM | Loyalty program for 12+ month customers | 90%+ long-term retention | 60 days |
| LOW | Exit surveys for churned customers | Identify true pain points | Ongoing |

## 🎯 Expected ROI

- **Customers Saved:** 605/year
- **Revenue Impact:** +$39,325 annually (assuming $65 ARPU)
- **Program Cost:** ~$20,000
- **Net Benefit:** +$19,325 | **97% ROI Year 1**

## 🛠️ Tools & Technologies

- **R** — Data analysis, visualization, statistical testing
- **R Markdown** — Reproducible analysis and reporting
- **ggplot2** — Data visualization
- **dplyr & tidyr** — Data wrangling

## 📁 Files in This Repo

- `churn_analysis_template.Rmd` — Full R analysis (reproducible)
- `churn_analysis_report.docx` — Executive summary with visualizations
- `data/` — Original dataset
- `outputs/` — HTML report

## 📚 Skills Demonstrated

✅ Cohort Analysis  
✅ Statistical Testing (t-tests, correlation)  
✅ Data Visualization (retention curves, histograms)  
✅ Business Insight Generation  
✅ Reproducible Research (R Markdown)  

---

**Created:** April 2026 | **Status:** Complete
