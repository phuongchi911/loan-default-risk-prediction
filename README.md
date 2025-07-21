# Loan Default Risk Prediction – Real Dataset (GMSC)

This project uses the **“Give Me Some Credit”** dataset to build and evaluate machine learning models that predict the likelihood of loan default. It simulates a real-world credit risk use case and demonstrates the full data science workflow — from cleaning and feature engineering to modeling, evaluation, and explainability.

---

## Project Structure

---

##  Workflow Summary

### 1. **Data Cleaning & Preparation**
- Removed nulls in income and dependents
- Created custom features (e.g., `loan_to_income`, `log_income`)
- Stratified sampling to handle class imbalance

### 2. **Modeling**
Trained and compared 3 models:
| Model                | ROC-AUC | Notes                            |
|----------------------|---------|----------------------------------|
| Logistic Regression  | ~0.81   | Interpretable baseline           |
| Random Forest        | ~0.84   | Strong performance, non-linear   |
| XGBoost              | ~0.86   | Best accuracy, used for SHAP     |

### 3. **Evaluation**
- Metrics: ROC-AUC, Precision, Recall, F1
- Combined ROC curve to visualize model performance

##  Key Takeaways

- **XGBoost** provided the highest predictive power across all metrics.
- Project demonstrates ability to work with **real-world, noisy data** and apply **explainable machine learning**.

---

## Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost
- Matplotlib, Seaborn

---

## Skills Demonstrated

- Credit risk modeling with real data
- Feature engineering for financial applications
- Model comparison and metric-driven selection
---

## Source

Dataset: [Kaggle – Give Me Some Credit](https://www.kaggle.com/c/GiveMeSomeCredit)




