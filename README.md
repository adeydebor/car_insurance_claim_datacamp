# Car Insurance Claim Prediction

## Overview
This project builds logistic regression models to predict whether a customer will file an insurance claim. The goal is to identify the **single most predictive feature** for accurate classification, enabling deployment of a simple, interpretable model. Accuracy is used to evaluate performance.

This analysis was completed as part of a DataCamp project using real-world customer data. (https://app.datacamp.com/learn/projects/modeling_car_insurance_claim_outcomes)

## Project Objectives
- Preprocess and clean customer insurance data.
- Build logistic regression models using individual features.
- Identify the best-performing feature based on accuracy.

## Technologies Used
- **R**
- readr, dplyr
- glue
- yardstick

## Files Included
- `car_insurance_claim.Rmd` – R Markdown with all code, results, and summary.
- `README.md` – Project overview and setup guide.
- `car_insurance.csv` – Dataset of customer profiles and insurance claim outcomes.

## How to Run
1. Clone this repository.
2. Open `car_insurance_claim.Rmd` in RStudio.
3. Run all code chunks or knit to HTML to view the analysis and results.

## Results Summary
- The best-performing feature for predicting insurance claim outcomes was identified using logistic regression.
- The final output includes the **most accurate single predictor** and its associated **accuracy score**.
