# 🧪 Cancer Labtest Data – ETL & ML Take-Home Assessment

This project is a take-home assessment focused on cleaning messy healthcare data, building an efficient ETL pipeline, and outlining a predictive machine learning task.

The dataset simulates lab test orders from a cancer diagnostics facility, including categories such as Histology, Cytology, Haematology, and Immunohistochemistry.

---

## 🚀 Project Deliverables

This repository contains:

| File | Description |
|------|-------------|
| `Deliverables.md` | Full documentation: assumptions, ETL summary, and machine learning task write-up |
| `cleaned_dataset.csv` | Final cleaned version of the raw lab test data |
| `cleaned_labtest.db` | Structured SQLite database generated from the ETL pipeline |
| `labtest-dataset-challenge.ipynb` | Kaggle notebook with all the code: data cleaning, EDA, transformation, and export |

---

## 📂 Summary of Tasks

### ✅ Task 1: Data Cleaning & Standardization
- Fixed missing and ambiguous values
- Standardized date formats
- Cleaned price fields and corrected typos
- Retained rows with non-fatal data issues
- Output: `cleaned_dataset.csv`

### ✅ Task 2: ETL Pipeline
- Raw data ingested and cleaned using `pandas`
- Final dataset exported to SQLite using `sqlite3`
- Output: `cleaned_labtest.db`
- Process explained in `Deliverables.md`

### ✅ Task 3: Machine Learning Use-Case
- Use case: Predicting lab test delays
- Target variable: `delay_days = signout_date - creation_date`
- Suggested models: Random Forest, XGBoost, Linear Regression
- Evaluation metrics: MAE, RMSE
- Full plan in `Deliverables.md`

---

## 📎 Notes
- Code and outputs are contained in `data-engineering-ai.ipynb`.
- A standalone `.py` ETL version can be created if required.
- All key decisions, assumptions, and ML strategy are documented in the `Deliverables.md` file.

---

## 💼 Context
Prepared for a job interview assessment to demonstrate:
- Data wrangling in healthcare
- Building an ETL pipeline
- Designing a predictive ML task for operational efficiency
📘 View the original notebook on Kaggle: [Kaggle Notebook – Data Engineering & AI](https://www.kaggle.com/code/ronkenoly/labtest-dataset-challenge/edit)

