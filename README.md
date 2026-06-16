# Global Tax Reform & Entrepreneurship Analysis

AI-driven analysis of how tax structures affect entrepreneurship across 196 countries using 43 years of World Bank data (1980–2022).

Completed as part of a Master of Business Analytics Capstone at Sunway University (May 2026).

## Key Results
- **XGBoost Regressor:** R² of 0.8437 — 215% improvement over the OLS baseline
- **Random Forest Classifier:** 91.49% accuracy predicting national income groups from tax data
- **Key finding:** Countries with a CIT-to-VAT ratio below 0.44 consistently show higher business formation rates
- Model accurately predicted entrepreneurship declines during the 2008 Financial Crisis and COVID-19

## Tech Stack
Python, XGBoost, Random Forest, SHAP, Pandas, Scikit-learn, Gradio

## Files
| File | Description |
|---|---|
| `CodeFile_Data_Cleaning.ipynb` | Data wrangling & missing value imputation |
| `CodeFile_of_EDA_&_ML_Model.ipynb` | EDA, feature engineering & ML modelling |
| `Final_Clean_Dataset.xlsx` | Cleaned dataset |
