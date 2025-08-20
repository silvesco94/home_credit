# Credit Default Risk — Work Project

This project demonstrates an end-to-end workflow for predicting the probability that an applicant will default on a loan. It includes the problem framing, exploratory analysis, reproducible modeling, and a stakeholder-facing presentation.

---

## [Business Problem Statement](./Business%20Problem%20Statement%20Template.pdf)

**Goal.** Enable more confident credit decisions by estimating the likelihood of default for new applicants.

**Why it matters.** Accurate risk estimates help widen access to credit while keeping portfolio risk within target bounds.

**Success criteria.**
- Primary metric: ROC–AUC on a held-out set
- Secondary: calibration quality and lift in high-risk deciles
- Constraints: model transparency, operational latency, and fairness considerations

**Scope.** Supervised classification using application and bureau features; model monitored post-deployment with drift checks.

---

## [Exploratory Data Analysis (EDA)](./eda.html)

**What’s covered.**
- Data health checks: missingness patterns, outliers, and type coercions  
- Target behavior: class imbalance and baseline risk by key segments  
- Feature understanding: distributions, correlations, and leakage screening  
- Early signal: univariate/bi-variate relationships and partial patterns that inform feature engineering

**Key takeaways.**
- Imbalance requires stratified CV and thresholding tuned to business costs  
- Several categorical features show strong separation after encoding  
- Some correlated features were consolidated to reduce redundancy

---

## [Modeling Workflow (R Markdown)](./modeling%20assignment.Rmd)

**Approach.**
- Baselines: logistic regression with regularization for interpretability  
- Tree-based learners: gradient boosting (e.g., XGBoost/GBM) for non-linear signal  
- Handling imbalance: class weights and probability threshold optimization  
- Validation: stratified k-fold cross-validation with a locked test split  
- Explainability: permutation importance and partial-dependence style checks

**Outputs.**
- Reproducible training pipeline
- Feature importance summary and calibration plots
- Exported probabilities for threshold tuning and decile analysis

_Run this file in RStudio to reproduce the analysis and knit artifacts._

---

## [Presentation & Findings](./presentation.pdf)

**Audience.** Product, risk, and operations stakeholders.

**Highlights.**
- Problem framing and business impact  
- Data overview and safeguards against leakage  
- Model performance (ROC–AUC, lift by decile) and trade-offs  
- Recommendation on operating threshold aligned to expected cost/benefit  
- Next steps: monitoring plan, feature pipeline hardening, and fairness checks

---

### How to Navigate
1. Start with the **Business Problem Statement** for context and KPIs.  
2. Open the **EDA** to understand the data and early signal.  
3. Review the **Modeling Workflow** to see the training/validation approach.  
4. Use the **Presentation** for an executive summary of results and decisions.

---
