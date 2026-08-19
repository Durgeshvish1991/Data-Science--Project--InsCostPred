# Insurance Cost Prediction

## Problem Statement
Predict the medical insurance cost (charges) for an individual based on personal and health-related attributes, to help understand what factors drive higher insurance costs.

## Dataset
- Source: Insurance cost dataset (Kaggle) — [add your dataset link here]
- Features: age, sex, BMI, number of children, smoker status, region
- Target variable: `charges` (medical insurance cost)

## Approach
1. Performed data cleaning and exploratory data analysis (EDA) to understand relationships between features and insurance cost.
2. Encoded categorical variables (sex, smoker, region) for model input.
3. Trained a Linear Regression model to predict insurance charges.
4. Evaluated the model using R² score.
5. The model achieved an R² score of ~0.75–0.77, a decent baseline for this dataset.

## Key Insights
- Smoker status and BMI showed a strong relationship with insurance cost — smokers and higher-BMI individuals tend to have significantly higher charges.
- Linear Regression gave a reasonable baseline; a tree-based model (Random Forest/XGBoost) could likely improve on this R² by capturing non-linear interactions between features.
- Findings can help insurers understand key cost drivers when setting premiums.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn (Linear Regression), Matplotlib/Seaborn

## How to Run
Open `Insurance Cost Prediction.ipynb` in Jupyter Notebook or Google Colab and run all cells.
Requires: Python 3.x, pandas, numpy, scikit-learn, matplotlib, seaborn (see Tech Stack above).
