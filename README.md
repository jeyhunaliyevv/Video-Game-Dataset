# Video Game Sales Analysis & Prediction

## Overview
This project explores video game sales data and builds baseline machine learning models to predict **Global_Sales**. It includes data cleaning, exploratory analysis, encoding of categorical variables, and model evaluation.

## Dataset
Typical columns in the dataset:
- **Name**, **Platform**, **Year**, **Genre**, **Publisher**
- **NA_Sales**, **EU_Sales**, **JP_Sales**, **Other_Sales**, **Global_Sales** *(target)*

> Note: If the dataset file cannot be shared publicly, include a short note on where to download it and place it under `data/`.

## Approach
- Data loading and basic profiling
- Missing value handling
- Exploratory Data Analysis (EDA)
- Encoding categorical features (e.g., Platform, Genre, Publisher)
- Baseline modeling (e.g., Random Forest Regressor)
- Evaluation (e.g., RMSE / R²)

## Repository Structure
- `VIDEO GAMES SALES.ipynb` — notebook with EDA and modeling
- `requirements.txt` — dependencies
- `README.md` — project summary

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook "VIDEO GAMES SALES.ipynb"
