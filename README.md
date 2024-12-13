Crime Rates and Housing Vacancies: A State-Level Study
Overview
This research investigates the relationship between non-violent crime levels and residential vacancy rates across different states in the US. Using a comprehensive dataset combining US Census, LEMAS survey, and FBI UCR data, we analyzed how crime rates predict housing vacancies while considering various socioeconomic factors.
Key Findings

Strong correlation between non-violent crimes (particularly larcenies and burglaries) and housing vacancies
Homelessness significantly influences the relationship between crime and vacancies, increasing the model's predictive power by 2.9%
Housing market factors (median rent and income) showed complex relationships but minimal direct impact on vacancy predictions
Population density had no significant impact on the relationship between crime and vacancies

Methodology

Utilized multiple statistical approaches including:

Linear Regression
Random Forest Classification
Gradient Boosting
Logistic Regression
Decision Trees
Naive Bayes


Implemented 5-fold cross-validation for model validation
Created new features like drug_units_ratio to enhance model performance
Handled missing data using KNN imputation techniques

Model Performance

Random Forest emerged as the best performing model with:

69.3% accuracy
69.4% F1-Score
84.7% ROC-AUC score


Linear regression explained 48.4% of variance in housing vacancies
Models showed better prediction accuracy for high and low vacancy areas compared to medium vacancy regions

Theoretical Framework
The research was grounded in two main theories:

Social Disorganization Theory: Explains how weakened social cohesion fosters crime
Broken Windows Theory: Demonstrates how visible neglect exacerbates disorder

Implications

Results suggest the need for integrated approaches to address both crime and housing vacancy issues
Highlights the importance of social stability over purely economic factors in predicting housing vacancies
Provides evidence-based insights for policymakers and urban planners

Limitations

Dataset age (early 90s) may not reflect current trends
Significant missing values in community-level data necessitated state-level analysis
Some variables showed complex relationships requiring further investigation

Research Team

Alyssa Day
Isabella Kleckner
Samy Babikerali
Togaa Lavien

University of North Carolina at Charlotte, DTSC 3602
