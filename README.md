# Video-Game-Dataset
## Game Sales Analysis

This project analyzes video game sales data to predict global sales using various machine learning models. The analysis includes data cleaning, feature engineering, model training, and evaluation.

## Dataset

The dataset contains video game sales data with the following columns:
- **Rank**: The ranking of the game based on global sales.
- **Name**: The name of the game.
- **Platform**: The platform on which the game was released.
- **Year**: The release year of the game.
- **Genre**: The genre of the game.
- **Publisher**: The publisher of the game.
- **NA_Sales**: Sales in North America (in millions).
- **EU_Sales**: Sales in Europe (in millions).
- **JP_Sales**: Sales in Japan (in millions).
- **Other_Sales**: Sales in other regions (in millions).
- **Global_Sales**: Total global sales (in millions).


### Prerequisites

- Python 3.6+
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

### Installation

Clone the repository:

git clone https://github.com/jeyhunaliyevv/game-sales-analysis.git
cd game-sales-analysis

cd game-sales-analysis
Install the required packages:
pip install -r requirements.txt
Usage
*Run the Jupyter notebook to see the analysis and model training:
*jupyter notebook "VIDEO GAMES SALES.ipynb"

Analysis Steps
Data Cleaning: Handling missing values and converting categorical data to numerical using OrdinalEncoder.
Exploratory Data Analysis (EDA): Visualizing data distribution and detecting outliers using box plots.
Feature Engineering: Selecting relevant features for model training.
Model Training: Training a Random Forest model to predict global sales.
Model Evaluation: Evaluating model performance using Mean Squared Error (MSE) and R2 Score on both training and test sets.

Example Code
Here is an example of how the model is trained and evaluated:
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, r2_score
from sklearn.preprocessing import OrdinalEncoder
import seaborn as sns
import matplotlib.pyplot as plt

# Logistic Regression Model for Video Game Sales Prediction

This project implements a logistic regression model to predict video game sales. The model's performance is evaluated using metrics such as F1 Score, Gini Score, and a confusion matrix.

## Model Performance

- **F1 Score**: 0.85
- **Gini Score**: 0.83

### Confusion Matrix

|            | Predicted Negative | Predicted Positive |
|------------|--------------------|--------------------|
| Actual Negative | 127                | 18                 |
| Actual Positive | 27                 | 128                |

## Getting Started

### Prerequisites

- Python 3.6+
- Pandas
- NumPy
- Scikit-learn

### Installation

Clone the repository:

Logistic Regression Model for Video Game Sales Prediction
This project implements a logistic regression model to predict video game sales. The model's performance is evaluated using metrics such as F1 Score, Gini Score, and a confusion matrix.
Model Performance
F1 Score: 0.85
Gini Score: 0.83
Confusion Matrix
Predicted Negative	Predicted Positive
Actual Negative	127	18
Actual Positive	27	128
Author
Your Jeyhun
Contact: jeyhun.aliyevv01@gmail.com
