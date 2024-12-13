<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crime Rates and Housing Vacancies: A State-Level Study</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            color: #34495e;
            margin-top: 25px;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        .team-section {
            background-color: #f7f9fc;
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
        }
        .key-finding {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Crime Rates and Housing Vacancies: A State-Level Study</h1>

    <h2>Overview</h2>
    <p>This research investigates the relationship between non-violent crime levels and residential vacancy rates across different states in the US. Using a comprehensive dataset combining US Census, LEMAS survey, and FBI UCR data, we analyzed how crime rates predict housing vacancies while considering various socioeconomic factors.</p>

    <h2>Key Findings</h2>
    <ul>
        <li class="key-finding">Strong correlation between non-violent crimes (particularly larcenies and burglaries) and housing vacancies</li>
        <li class="key-finding">Homelessness significantly influences the relationship between crime and vacancies, increasing the model's predictive power by 2.9%</li>
        <li class="key-finding">Housing market factors (median rent and income) showed complex relationships but minimal direct impact on vacancy predictions</li>
        <li class="key-finding">Population density had no significant impact on the relationship between crime and vacancies</li>
    </ul>

    <h2>Methodology</h2>
    <p>We utilized multiple statistical approaches including:</p>
    <ul>
        <li>Linear Regression</li>
        <li>Random Forest Classification</li>
        <li>Gradient Boosting</li>
        <li>Logistic Regression</li>
        <li>Decision Trees</li>
        <li>Naive Bayes</li>
    </ul>
    <p>The research implemented 5-fold cross-validation for model validation, created new features like drug_units_ratio to enhance model performance, and handled missing data using KNN imputation techniques.</p>

    <h2>Model Performance</h2>
    <ul>
        <li>Random Forest emerged as the best performing model with:
            <ul>
                <li>69.3% accuracy</li>
                <li>69.4% F1-Score</li>
                <li>84.7% ROC-AUC score</li>
            </ul>
        </li>
        <li>Linear regression explained 48.4% of variance in housing vacancies</li>
        <li>Models showed better prediction accuracy for high and low vacancy areas compared to medium vacancy regions</li>
    </ul>

    <h2>Theoretical Framework</h2>
    <p>The research was grounded in two main theories:</p>
    <ul>
        <li><strong>Social Disorganization Theory:</strong> Explains how weakened social cohesion fosters crime</li>
        <li><strong>Broken Windows Theory:</strong> Demonstrates how visible neglect exacerbates disorder</li>
    </ul>

    <h2>Implications</h2>
    <ul>
        <li>Results suggest the need for integrated approaches to address both crime and housing vacancy issues</li>
        <li>Highlights the importance of social stability over purely economic factors in predicting housing vacancies</li>
        <li>Provides evidence-based insights for policymakers and urban planners</li>
    </ul>

    <h2>Limitations</h2>
    <ul>
        <li>Dataset age (early 90s) may not reflect current trends</li>
        <li>Significant missing values in community-level data necessitated state-level analysis</li>
        <li>Some variables showed complex relationships requiring further investigation</li>
    </ul>

    <div class="team-section">
        <h2>Research Team</h2>
        <ul>
            <li>Alyssa Day</li>
            <li>Isabella Kleckner</li>
            <li>Samy Babikerali</li>
            <li>Togaa Lavien</li>
        </ul>
        <p><em>University of North Carolina at Charlotte, DTSC 3602</em></p>
    </div>
</body>
</html>
