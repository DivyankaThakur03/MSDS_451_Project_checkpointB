# MSDS 451 Project: Checkpoint B

## Project Overview  
Building on Checkpoint A, this project develops a complete algorithmic trading system for NVDA with directional forecasting and risk-free asset allocation.

---

## Key Improvements from Checkpoint A

**Fixed class imbalance** - Model now predicts both UP and DOWN days (SMOTE)  
**Added market features** - VIX, S&P 500 returns, Treasury yields  
**Built trading strategy** - NVDA vs. cash allocation system  
**Multiple models** - Logistic Regression, Random Forest, XGBoost  
**Performance metrics** - Sharpe ratio, alpha, beta, maximum drawdown  

---

## Repository Contents

| File | Description |
|---|---|
| `Report_checkpointB.pdf` | Research report with methodology, results, and performance analysis |
| `code_checkpointB.ipynb` | Jupyter Notebook with complete implementation |

---

## How to Run
```bash
pip install pandas numpy scikit-learn xgboost yfinance imbalanced-learn matplotlib seaborn
jupyter notebook code_checkpointB.ipynb
```

---

**Author:** Divyanka Thakur  
**Date:** October 2025
