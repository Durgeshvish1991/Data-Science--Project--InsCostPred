# Insurance Claim Prediction

## Problem Statement
An insurance company wants to predict which customers are likely to file a claim in the next year, so it can price policies more accurately and flag high-risk customers for review.

## Dataset
- Source: Kaggle — [add your dataset link here]
- Customer and policy-level data (demographics, vehicle/policy details)
- Target variable: claim likelihood (1 = will file a claim, 0 = will not)
- Severe class imbalance in the target variable

## Approach
1. Performed extensive data cleaning and EDA to understand feature relationships and imbalance.
2. Balanced the severe class imbalance using up-sampling.
3. Trained and evaluated three models: Logistic Regression, Decision Tree, and Random Forest.
4. Decision Tree delivered the strongest results, with ~97% accuracy in identifying claim-prone customers.

## Key Insights
- Decision Tree captured non-linear patterns in the data better than Logistic Regression for this dataset.
- Careful handling of class imbalance was critical — without up-sampling, the model would simply predict "no claim" for almost every customer and still look accurate.
- Findings can support risk-based pricing and help the company flag high-risk policyholders early.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn (Decision Tree, Random Forest, Logistic Regression), Matplotlib/Seaborn

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
