<div align="center">

# Dhruv Rajpoot

**Product Analyst** &nbsp;·&nbsp; Ex-Litigation Attorney, Delhi High Court &nbsp;·&nbsp; Delhi, India

*Focused on answering one question: what moves the metric?*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruvrajpoot)
[![Portfolio](https://img.shields.io/badge/Portfolio-1B4F8A?style=for-the-badge&logo=github&logoColor=white)](https://mr-dhruvrajpoot.github.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhruv.rajpoot@outlook.com)

</div>

---

## About

Before moving into analytics, I spent 5+ years as a litigation attorney at the Delhi High Court — working in evidence analysis, GDPR, and commercial law.

That background shaped how I approach data work: **start with the question that matters to the business, then build backward to the analysis.**

Since 2023, I've worked as a Product Analyst across SaaS environments — focused on activation, retention, churn diagnostics, and reporting infrastructure. I don't just run analysis. I identify where metrics are breaking and drive the decision that fixes them.

---

## Experience

**Product Analyst** &nbsp;·&nbsp; Silentfloor Technologies &nbsp;·&nbsp; Full-time · Remote &nbsp;·&nbsp; Dec 2024 – Jan 2026
- +14 percentage points activation lift by identifying a 68% onboarding drop-off via SQL cohort analysis and executing a product fix within one sprint — root cause to production in a single engagement
- Reduced reporting latency from 3 days to same-day by building a 15-metric KPI dashboard suite in SQL + Power BI, eliminating manual aggregation entirely
- Eliminated 4.5 hours/week of manual reporting by deploying a Python automation pipeline (Pandas + IQR anomaly detection), reducing execution time to 2 seconds
- Reduced customer success intervention by 30% by implementing data-driven onboarding improvements based on user behaviour analysis

**Product Analyst** &nbsp;·&nbsp; GC4 Tech International &nbsp;·&nbsp; Full-time · Remote &nbsp;·&nbsp; Feb 2024 – Nov 2024
- 22% reduction in customer acquisition cost over two quarters through SQL-based segmentation and attribution analysis used directly in growth strategy execution
- Saved 8 analyst hours/week (70% effort reduction) by automating recurring reporting workflows in Python — time permanently redirected to higher-value analysis
- Replaced fragmented reporting across 4 departments with a unified SQL + Power BI dashboard system, creating a single source of truth adopted org-wide
- Influenced quarterly budget allocation by delivering Tableau dashboards translating campaign and product performance into actionable spend decisions for senior leadership

**Data Analyst — Contract Engagement** &nbsp;·&nbsp; Dataiku &nbsp;·&nbsp; Contract · Remote &nbsp;·&nbsp; Jan 2023 – Jan 2024
- 74% precision churn prediction model (Random Forest, ROC-AUC 0.78) identifying 18% of high-risk accounts 30 days pre-churn — enabling proactive retention before revenue was lost
- Reduced data preparation time by 20 hours/week by building Python ETL pipelines consolidating multi-source product and customer data into a single clean dataset
- Replaced manual Excel reporting with Tableau dashboards adopted for weekly product and revenue strategic reviews

**Litigation Attorney** &nbsp;·&nbsp; High Court of Delhi &nbsp;·&nbsp; Full-time &nbsp;·&nbsp; Sep 2017 – Jan 2023
- Built defensible, evidence-based conclusions from incomplete and contradictory data across 100+ cases — the same structured analytical reasoning now applied to product and growth decisions
- Specialised in GDPR, IP law, arbitration, and company law — legal grounding that now informs data governance, compliance frameworks, and regulated SaaS environments

---

## Selected Outcomes

| Problem | Analysis | Decision & Impact |
|---|---|---|
| 68% onboarding drop-off killing activation | SQL cohort funnel — KYC step identified as bottleneck | Product fix shipped in one sprint · **+14pp activation lift** |
| Unknown churn timing and causes | Who/when/why diagnosis before modelling — Sales roles, 12–18 month tenure | Retention spend targeted at highest-risk cohort · **ROC-AUC 0.78, 74% precision** |
| 4.5 hrs/week lost to manual reporting | Python pipeline with IQR anomaly detection + auto-generated summaries | **Zero analyst intervention** required · execution time → 2 seconds |
| CAC spread across low-ROI segments | SQL segmentation and attribution analysis across acquisition channels | Budget reallocated to highest-yield segments · **22% CAC improvement** |
| Regional performance gaps hidden in headline numbers | KPI hierarchy: company → region → category → SKU across 155K transactions | Lagging regions surfaced · **revenue variance up to 3× identified** |

---

## Featured Projects

### 🔁 [Activation Optimisation — Bank Campaign A/B Analysis](https://github.com/Mr-DhruvRajpoot/bank-campaign-activation-analysis)

**Problem:** Only 32% of users completed onboarding — KYC step was the activation bottleneck.

**Analysis:** Funnel breakdown by step, segmented by session time at KYC. Users spending >5 min converted at 3–4× the average. Chi-square testing validated segment-level significance (p < 0.05). March, September, October identified as highest-conversion windows.

**Decision & impact:** Guided KYC flow + friction reduction. A/B test simulated **+14pp activation lift** over baseline.

`Python` `scipy` `Chi-square testing` `Funnel analysis` `Segmentation`

---

### 🤖 [Churn Diagnostics & Retention Strategy](https://github.com/Mr-DhruvRajpoot/employee-churn-prediction)

**Problem:** High attrition raising replacement cost — business needed to know who churns, when, and why before spending on retention.

**Who · When · Why:** Sales and junior roles churn at 2.4× base rate · exit concentrates at 12–18 month tenure · overtime + low satisfaction = near-certain exit (high-satisfaction overtime workers stayed).

**Decision & model:** Retention spend targeted at Sales roles at 12-month mark. Random Forest (ROC-AUC **0.78**, 74% precision) ranks individuals for intervention — model comes last, after the diagnosis.

`scikit-learn` `Random Forest` `Cohort analysis` `Feature importance` `ROC-AUC`

---

### 🔁 [Sales Reporting Automation & Data Pipeline](https://github.com/Mr-DhruvRajpoot/Sales-reporting-automation-)

**Problem:** 4.5 hours of weekly manual Excel work blocked growth decisions — reports arrived too late to act on.

**Decision & impact:** Python pipeline replaced the full manual cycle. IQR-based anomaly detection, intelligent imputation, and auto-generated executive summaries. **Zero code changes** needed for new periods or regions. Execution time: 4.5 hrs → 2 seconds.

`Python` `pandas` `NumPy` `matplotlib` `ETL`

---

### 📈 [KPI Hierarchy & Growth Measurement — 155K Transactions](https://github.com/Mr-DhruvRajpoot/retail-kpi-growth-dashboard)

**Problem:** Leadership had no view of whether growth was uniform — some regions were masking underperformance inside a positive headline number.

**Decision & impact:** Full KPI framework: company → region → category → SKU. Lagging regions isolated and flagged for resource reallocation. Revenue per customer varies **up to 3×** across regions.

`Python` `pandas` `KPI Framework` `YoY Analysis`

---

### ✈️ [Revenue Yield & CAC Efficiency — Flight Booking Segments](https://github.com/Mr-DhruvRajpoot/flight-booking-cac-analysis)

**Problem:** Marketing budget spread evenly across routes and seat classes — no visibility into which segments generated the best revenue-per-acquisition.

**Insight:** Business class on short-haul routes has 60% higher yield per seat than long-haul economy. Early bookers (30–90 days) pay premium fares — high-intent segment identified for campaign focus.

**Decision:** Reallocate acquisition budget toward short-haul business and early-booking economy. Deprioritise last-minute economy campaigns.

`Python` `pandas` `Revenue Analysis` `CAC Modelling`

---

### 🍷 [Wine Quality End-to-End Analysis](https://github.com/Mr-DhruvRajpoot/Wine-quality-endtoend-)

End-to-end analyst workflow on 4,898 wine batches. SQL cohort analysis using window functions, CASE WHEN, and aggregations. Python EDA followed by Random Forest prediction (AUC ~0.85) and production recommendations.

`SQL` `Python` `Random Forest` `Window Functions`

---

## Tech Stack

**Tools**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Analysis**

![Funnel Analysis](https://img.shields.io/badge/Funnel%20Analysis-2ECC71?style=flat-square)
![Cohort Analysis](https://img.shields.io/badge/Cohort%20Analysis-2ECC71?style=flat-square)
![A/B Testing](https://img.shields.io/badge/A%2FB%20Testing-2ECC71?style=flat-square)
![Churn Diagnostics](https://img.shields.io/badge/Churn%20Diagnostics-2ECC71?style=flat-square)
![Segmentation](https://img.shields.io/badge/Segmentation-2ECC71?style=flat-square)
![ETL Pipelines](https://img.shields.io/badge/ETL%20Pipelines-2ECC71?style=flat-square)
![KPI Framework Design](https://img.shields.io/badge/KPI%20Framework%20Design-2ECC71?style=flat-square)

**Domain**

![SaaS](https://img.shields.io/badge/SaaS-1B4F8A?style=flat-square)
![Growth](https://img.shields.io/badge/Growth-1B4F8A?style=flat-square)
![Retention](https://img.shields.io/badge/Retention-1B4F8A?style=flat-square)
![Fintech](https://img.shields.io/badge/Fintech-1B4F8A?style=flat-square)
![GDPR / Data Governance](https://img.shields.io/badge/GDPR%20%2F%20Data%20Governance-1B4F8A?style=flat-square)

---

## GitHub Stats

<div align="center">

![Dhruv's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mr-DhruvRajpoot&show_icons=true&theme=default&hide_border=true&title_color=1B4F8A&icon_color=1B4F8A&text_color=333333&bg_color=ffffff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Mr-DhruvRajpoot&layout=compact&hide_border=true&title_color=1B4F8A&text_color=333333&bg_color=ffffff)

</div>

---

## Background Note

The legal background is not a footnote — it is a differentiator.

Six years of forensic evidence analysis, arguing from incomplete and contradictory information, and communicating high-stakes conclusions to decision-makers under pressure. Those are the same skills that make a product analyst effective. The domain changed. The thinking didn't.

I hold a **Data Protection Officer certification** and have direct experience with GDPR in a litigation context — not only in documentation.

---

<div align="center">

**Currently open to Product Analyst and Growth Analyst roles in SaaS or Fintech — remote or Delhi-based.**

[dhruv.rajpoot@outlook.com](mailto:dhruv.rajpoot@outlook.com) &nbsp;·&nbsp; [linkedin.com/in/dhruvrajpoot](https://linkedin.com/in/dhruvrajpoot)

</div>
