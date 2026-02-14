# Video Game Sales Analysis & Prediction

## Overview
This project explores video game sales data and builds baseline machine learning models to predict **Global_Sales**. It includes data cleaning, exploratory analysis, encoding of categorical variables, and model evaluation.

## Dataset
Typical columns in the dataset:
- **Name**, **Platform**, **Year**, **Genre**, **Publisher**
- **NA_Sales**, **EU_Sales**, **JP_Sales**, **Other_Sales**, **Global_Sales** *(target)*

## Approach 
- Data loading and basic profiling
- Missing value handling
- Exploratory Data Analysis (EDA)
- Encoding categorical features (e.g., Platform, Genre, Publisher)
- Baseline modeling (e.g., Random Forest Regressor)
- Evaluation (e.g., RMSE / R²)

## Repository Structure
- video_game_sales_analysis.ipynb — notebook with EDA and modeling
- requirements.txt — dependencies
- README.md — project summary

## How to Run
pip install -r requirements.txt
jupyter notebook "video_game_sales_analysis.ipynb"

## Results
- Model: Random Forest Regressor (depth tuning)
- Best test R²: 0.9018 (depth=10)
- Train R² (best): 0.9458
- Generalization gap (train-test): 0.0440

## License
MIT License
