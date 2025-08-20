# Home Credit Default Risk – Team Project

Predict which applicants are likely to default so Home Credit can expand access to credit while managing risk. Primary KPI: AUC on a held-out set.

> Team: Ahsan Ahmed · Raunak Sharma · Scott Silverstein · Rylan Tribush

---

## 📁 Repository Contents

- 📄 **Business Problem Statement**  
  Goals, scope, metrics, and benefits of the solution.  
  → [`Business Problem Statement Template.pdf`](./Business%20Problem%20Statement%20Template.pdf)

- 🖥️ **Annotated Presentation (PDF export)**  
  Slide deck summarizing data findings, class imbalance, feature importance, and model results (XGBoost).  
  → [`annotated-Presentation Draft 2.pptx.pdf`](./annotated-Presentation%20Draft%202.pptx.pdf)

- 📊 **EDA Report (HTML)**  
  Exploratory data analysis you can open in a browser.  
  → [`eda.html`](./eda.html)

- 🧪 **Modeling Notebook (R Markdown)**  
  Reproducible modeling workflow. Knit to HTML or save outputs as needed.  
  → [`modeling assignment.Rmd`](./modeling%20assignment.Rmd)

---

## 🔎 Project Overview

Home Credit aims to better identify creditworthy borrowers—including those with little or no traditional credit history—by using alternative data and supervised learning to predict default probability. The business value is improved risk management and broader financial inclusion, measured primarily with AUC.  
Modeling centers on gradient boosting (XGBoost) due to its handling of class imbalance, feature importance, and strong performance.

---

## 🧭 How to Use This Repo

1. **Skim the problem framing:** start with the _Business Problem Statement_ to understand objectives, scope, and KPIs.  
2. **Review EDA:** open `eda.html` in your browser to see data distributions and relationships.  
3. **Reproduce the model:** open `modeling assignment.Rmd` in RStudio and Knit/Run.  
4. **Share results:** use the _Annotated Presentation_ for a stakeholder-friendly summary.

---

## 🛠️ Tech & Metrics (at a glance)

- **Primary metric:** AUC on a held-out test set  
- **Modeling approach:** Gradient Boosting (XGBoost)  
- **Artifacts:** Business problem statement (PDF), EDA (HTML), R Markdown modeling file, annotated slide deck (PDF)

---

## 📬 Contact

Questions or suggestions? Open an issue or reach out to a team member (see author list above).
