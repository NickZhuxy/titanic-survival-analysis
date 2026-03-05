# Titanic Survival Analysis

Statistical analysis and predictive modeling of passenger survival on the RMS Titanic, using the [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data).

## Overview

This project investigates what factors influenced passenger survival through exploratory data analysis, hypothesis testing, correlation analysis, causal reasoning, and logistic regression modeling.

**Key findings:**
- Gender was the strongest predictor of survival (women had ~74% survival rate vs. men ~19%), driven by the "women and children first" evacuation protocol
- Passenger class significantly affected outcomes (1st: ~63%, 2nd: ~47%, 3rd: ~24%)
- A logistic regression model achieved ~85% accuracy with strong generalization

## Methods

- **Data cleaning**: Median imputation for age/fare, dropped cabin (77% missing), one-hot encoding for categorical features
- **Statistical tests**: Two-sample t-tests on age, SibSp, and Parch between survivors and non-survivors
- **Causal analysis**: Discussion of why the sex-survival correlation is not causal
- **Modeling**: Logistic regression with 80/20 stratified train-test split

## Tech Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, SciPy

## Project Structure

```
├── Final_Project_Titanic v9.ipynb   # Main analysis notebook
├── titanic.csv                      # Combined dataset (1,309 records)
├── traintitanic.csv                 # Training set (891 records)
├── testtitanic.csv                  # Test set (418 records)
├── Slides.pptx                     # Presentation slides
└── final_submission/                # Submission materials
```

## Authors

Kaiping Liu & Nick Zhu
