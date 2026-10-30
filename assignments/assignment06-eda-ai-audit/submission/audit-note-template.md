# Table 1 Audit Note

## Cohort

This analysis cohort was restricted to adults aged 20 to 80. It was implemented
by filtering for ages 20-30, and checking the row counts for those ages

## Missingness

The variables checked for missingness included BMI, age, income group, gender,
race and cycle

## Planted Issues

| Issue | Category | Why it matters | Corrected approach |
|---|---|---|---|
| no accounting for missing BMI values | Correctness | cannot compare BMI values across income groups as a result | in the R code, account for missing BMI values, and create a missingness table of key variables |
| missingness not reported before summary analysis | Reproducibility |makes the code less reproducible, if other people want to work on the document or simply verify the results  | include a missingness table for key variables before analysis |
| Implication of causation | Interpretation |falsely draws causative conclusions from a descriptive summary | remove deterministic/causative language and emphasise descriptive nature of results |
| no reference to stewardship | Stewardship | it does not identify what the data should and should not be used for, and why | include a stewardship note indicating what the dataset is, what it can claim/used for, how to cite, and any important considerations for AI use |
| large SD numbers | Correctness | age summaries become distorted by coding errors | go through code and ensure that missing values were not incorrectly coded as numbers |

## AI-Use Check

AI was used to verify how missing values are incorrectly coded into calculations. This was verified by independent google research of incorrect coding of missing values.
AI was aslo used ti draft the stewardship statement, and was cross-checked with stewardship guidelines provided by the text book.

##Stewardship statement
The data used in this analysis are derived from the National Health and Nutrition Examination Survey (NHANES), collected by the CDC's National Center for Health Statistics, 
and provided as a prepared dataset for classroom learning and analysis. 
The dataset is used for educational purposes to practice data cleaning, descriptive statistics, 
and reproducible analysis. Although the data are publicly available and de-identified, appropriate data stewardship 
requires protecting participant privacy and avoiding attempts to re-identify individuals.

