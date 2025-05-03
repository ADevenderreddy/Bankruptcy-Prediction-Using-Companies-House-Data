# 📊 Bankruptcy Prediction Using Companies House Data

This repository contains a data-driven analysis to predict bankruptcy risk among companies using financial and categorical attributes extracted from Companies House data. The goal is to aid stakeholders in identifying early warning signs of financial distress through exploratory data analysis and visualization.

---

## 🔍 Objective

To explore and analyze key features of companies that are predictive of bankruptcy, leveraging publicly available data and Python-based tools. The project aims to answer:

* What characteristics distinguish bankrupt vs. non-bankrupt companies?
* Are there sector-based or geographic patterns in bankruptcies?
* How do financial indicators correlate with company status?

---

## 🧰 Tools & Technologies

* **Python**
* **Pandas** for data manipulation
* **Seaborn / Matplotlib** for visualization
* **Jupyter Notebook** for analysis
* **MS Word** for reporting

---

## 📊 Dataset

The dataset `Company_House_Info.csv` includes:

* Company name
* Incorporation and dissolution dates
* Company status (Active, Dissolved)
* Company type (e.g., Private limited)
* SIC codes (industry classification)
* Region
* Key dates and events relevant to company lifecycle

---

## 📈 Key Insights (from `Company Document.docx`)

* A strong correlation was found between short operational lifespan and financial distress.
* Certain SIC codes and regions showed disproportionately high dissolution rates.
* Time-series analysis suggests clusters of bankruptcies around economic downturns.

*Full narrative and interpretations are provided in the Word document.*

---

## 📌 Future Work

* Integrate machine learning models for prediction (e.g., Logistic Regression, Random Forest)
* Include macroeconomic indicators for deeper context
* Build a dashboard for interactive analysis (e.g., with Plotly or Tableau)


