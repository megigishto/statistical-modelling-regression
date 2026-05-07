# Statistical Modelling – Regression Analysis

**Oxford Brookes University | MSc Data Science & Artificial Intelligence | 2025**

---

## Overview

This project investigates the clinical and lifestyle factors affecting 
systolic blood pressure using regression modelling techniques. 
The analysis is based on a personalised clinical dataset and covers 
both linear and logistic regression with full diagnostic evaluation.

---

## Key Techniques

- Dummy variable encoding for categorical predictors
- Multiple linear regression
- Model diagnostics:
  - Multicollinearity detection via VIF
  - Influential point detection via Cook's Distance
  - Heteroscedasticity testing
- Logistic regression with interaction terms
- Odds ratio interpretation

---

## Tools & Languages

Python | Statsmodels | Pandas | Scipy | Statistical Modelling

---

## Repository Structure

| File | Description |
|------|-------------|
| `multiple_linear_regression_exercise_1.py` | Annotated Python code for both regression models |
| `Report.pdf` | Full written report with interpretations and results |
| `cw1.csv` | Dataset used for the analysis |

---

## Key Findings

- Age, BMI, and Cholesterol were significant positive predictors of systolic blood pressure
- Logistic regression with interaction terms revealed nuanced relationships 
  between alcohol use, smoking status, and hypertension risk
- Diagnostic checks confirmed model validity with remedies applied where needed
