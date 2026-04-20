# Loan Default Risk Analysis

## Project Overview
This project analyzes loan default risk using a dataset of 150,000 real borrower records from the Kaggle "Give Me Some Credit" competition. The goal is to identify key factors that predict whether a borrower will experience serious financial distress within two years.

As a former banking professional with experience in personal banking and mortgage assessment, I built this project to combine my domain knowledge with data analytics skills.

## Tools & Technologies
- **Python** (pandas, matplotlib, seaborn, scikit-learn)
- **Power BI** (interactive dashboard)
- **Google Colab** (development environment)

## Dataset
- Source: [Give Me Some Credit — Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit)
- 150,000 borrower records
- Target variable: `SeriousDlqin2yrs` (1 = defaulted, 0 = no default)

## Income Group Definitions
| Group | Monthly Income |
|-------|---------------|
| Low | Below $3,000 |
| Medium | $3,000 – $6,000 |
| High | $6,000 – $10,000 |
| Very High | Above $10,000 |

## Key Findings
- Overall default rate: **6.68%**
- Borrowers under 30 have the highest default rate (~12%)
- Default rate decreases consistently with age — borrowers 60+ default at only ~3%
- Low income borrowers default at nearly 3x the rate of high income borrowers
- The most important predictor of default is **revolving credit utilization** (how much of available credit is being used)
- Random Forest model achieved **94% accuracy** with significantly better recall than Logistic Regression

## Project Structure
- `Kaggle.ipynb` — Full Python analysis (data cleaning, EDA, visualizations, ML model)
- `Loan_Default_Risk_Dashboard.pdf` — Power BI dashboard export
- `loan_default_for_powerbi.csv` — Processed dataset used for dashboard

## Skills Demonstrated
SQL · Python · Power BI · Exploratory Data Analysis · Data Cleaning · Machine Learning · Credit Risk · Data Visualization
