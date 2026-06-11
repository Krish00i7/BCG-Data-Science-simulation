# BCG Data Science Job Simulation

A end-to-end data science project completed as part of the **BCG X Data Science Job Simulation** on Forage (June 2026).

The project focuses on predicting customer churn for **PowerCo**, a major European energy utility, and recommending a data-driven retention strategy for the SME division.

---

## Problem Statement

PowerCo is losing SME customers to competitors following energy market liberalisation. The goal is to:
- Identify customers at risk of churning before they leave
- Understand the key drivers of churn
- Recommend a targeted retention strategy

---

## Project Structure

| File | Description |
|------|-------------|
| `BCG_task_1_EDA.ipynb` | Exploratory Data Analysis — understanding churn distribution, missing values, and feature patterns |
| `BCG_task_2_feature_engineering.ipynb` | Feature Engineering — creating price sensitivity features, transforming consumption and margin data |
| `BCG_task_3_randomforest.ipynb` | Model Building — Random Forest classifier for churn prediction |
| `BCG_task_4__Executive_summary.pdf` | Executive Summary — steering committee slide with findings and recommendations |

---

## Model Results

| Metric | Score |
|--------|-------|
| Accuracy | 89.9% |
| Precision | 71.4% |
| Recall | 4.9% |
| F1-Score | 9.2% |

> **Key Insight:** High accuracy but low recall indicates severe class imbalance. The model correctly identifies churn when it predicts it (71.4% precision) but misses most churning customers. Class balancing techniques such as SMOTE are recommended before deployment.

---

## Key Findings

- Churn rate is ~10% across ~14,606 SME customers
- **Price sensitivity is not the primary driver of churn**
- Net margin and yearly consumption are the strongest churn indicators
- A blanket discount strategy is not recommended — targeted retention for high-risk, high-value customers is more effective

---

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (Random Forest)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Certificate

[BCG X Data Science Job Simulation — Forage (June 2026)](https://www.theforage.com/completion-certificates/SKZxezskWgmFjRvj9/Tcz8gTtprzAS4xSoK_SKZxezskWgmFjRvj9_690b8f4146d3894b5c2b7372_1781167050740_completion_certificate.pdf)

---

## Author

**Krishnakumar M**  
B.Sc Computer Science — SRM Arts and Science College, Chennai  
[GitHub](https://github.com/Krish00i7) • [LinkedIn](https://linkedin.com/in/krishnakumar-m)
