# Credit-Card-Churn-Prediction
Churn prediction for credit-card customers with business-ready explanations. Pipelines, cross-validation, regularisation and up/down sampling; model selection via ROC/PR and feature importance. Python, scikit-learn.

**Commit message:** `Initial commit: Trade Ahead clustering notebook and README`

---

## 8) Credit Card Users Churn Prediction

```markdown
# Credit Card Users: Churn Prediction

Predict whether a customer will churn from a credit card service and explain the drivers of churn.

## Overview
- **Goal:** Classify churn vs non-churn and surface actionable drivers.
- **Techniques:** Cross-validation, regularisation (L1/L2), scikit-learn Pipelines, hyperparameter tuning, up/down sampling for imbalance.

## Data
Coursework dataset (not included). Add a small anonymised sample in `data/sample/` if possible.

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
