# Car Insurance Claim Prediction: An Actuarial Statistics Approach

## Executive Summary
Analysis of 58,592 motor policy records to identify and quantify the factors driving claim occurrence. This project applies actuarial statistical methods — probability modelling, hypothesis testing, regression, GLMs, and Bayesian credibility theory — to assess and price motor insurance risk.

## Business Objective
Build a statistical framework to estimate the probability of a policyholder making a claim, and identify which vehicle, policyholder, and regional characteristics are the strongest risk indicators — mirroring the underwriting and pricing questions an actuary addresses when segmenting a motor book.

## Dataset Overview
- **Records:** 58,592 policies
- **Target Variable:** `is_claim` (binary: claim / no claim in the policy period)
- **Key Features:** policyholder age, vehicle age, population density of area, vehicle segment, safety features (airbags, NCAP rating, ESC), engine specifications
- **Class Balance:** Claims are a minority class relative to non-claims, typical of insurance claim data

## Technical Skills Applied
- **Language:** R 
- **Statistical Methods:** Probability distributions, hypothesis testing (t-test, F-test), ANOVA, correlation, linear regression, generalized linear models (logistic regression), Bayesian credibility theory (EBCT)
- **Tools:** Base R, data aggregation, model fitting, data visualization

## Actuarial Relevance
This project demonstrates CS1-level actuarial competencies:
- Probability and distribution theory applied to claim frequency
- Statistical inference and significance testing
- Regression and GLM-based risk modelling
- Bayesian/credibility methods for risk segmentation (as used in experience rating)

## Files
- `motor-insurance-risk-claim-modelling.ipynb` - Main analysis
- `train.csv` - Dataset

## Kaggle Project
https://www.kaggle.com/code/architmehta1908/motor-insurance-risk-claim-modelling

## Author
Archit Mehta - Actuarial Aspirant (CM1, CS1)
