# 💰 Personal Finance & Expense Predictor

## Project Overview
The **Personal Finance & Expense Predictor** is an interactive tool that helps users track their daily expenses, generate insights, and predict future spending. By uploading a CSV file containing their expense history, users receive predictions for the next 30 days along with actionable recommendations to manage their finances better.

This project demonstrates skills in **data processing, predictive modeling, visualization, and building interactive web applications**.

---

## Features
- Upload a CSV file with your daily expenses (`Date` and `Amount` columns).  
- Automatic data preprocessing and cleaning.  
- Predict future expenses using **Linear Regression (time-series approach)**.  
- Visualize actual vs predicted expenses with plots.  
- Provides daily average expense and recommendations for saving.

---

## CSV Format
Your CSV file should have the following structure:

| Date       | Amount |
|------------|--------|
| 2025-12-01 | 45.5   |
| 2025-12-02 | 60.0   |
| 2025-12-03 | 32.7   |

- `Date` should be in `YYYY-MM-DD` format.  
- `Amount` is the daily expense as a number.

---

## Usage

### Run Locally (Python / Jupyter / Colab)
1. Install dependencies:
```bash
pip install gradio scikit-learn pandas matplotlib
