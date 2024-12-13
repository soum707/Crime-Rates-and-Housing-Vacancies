# Crime Rates and Housing Vacancies: A State-Level Study

## Overview
A data science research project analyzing the relationship between non-violent crime rates and housing vacancies across different states in the US. The study combines data from US Census, LEMAS survey, and FBI UCR to understand how crime patterns might predict housing vacancy rates.

## Dataset
* Combined data from US Census, LEMAS survey, and FBI UCR from early 90s
* Features include crime rates, housing metrics, demographic data, and socioeconomic indicators
* State-level analysis due to significant missing values in community-level data

## Key Findings
* Strong correlation found between non-violent crimes and housing vacancies
* Homelessness significantly impacts the crime-vacancy relationship (+2.9% model performance)
* Housing market factors showed complex but minimal direct impact
* Population density had no significant impact on the relationship

## Methods & Models
* Data preprocessing: KNN imputation, feature engineering
* Models implemented:
  * Linear Regression
  * Random Forest Classification
  * Gradient Boosting
  * Logistic Regression
  * Decision Trees
  * Naive Bayes
* Validation: 5-fold cross-validation

## Results
* Best performing model: Random Forest
  * Accuracy: 69.3%
  * F1-Score: 69.4%
  * ROC-AUC: 84.7%
* Linear regression explained 48.4% of variance in housing vacancies
* Better prediction accuracy for high and low vacancy areas

## Research Team
* Alyssa Day
* Isabella Kleckner
* Samy Babikerali
* Togaa Lavien

*University of North Carolina at Charlotte, DTSC 3602*
