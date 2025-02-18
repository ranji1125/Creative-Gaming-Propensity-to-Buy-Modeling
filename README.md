# Creative-Gaming-Propensity-to-Buy-Modeling

## Project Overview
This project involved developing a predictive model for Creative Gaming to identify potential buyers of the "Zalon campaign" from players of "Space Pirates". The focus was on comprehensive data analysis, model training, and evaluation to predict player behavior and enhance marketing strategies.

## Data Preparation and Exploratory Analysis
- **Dataset**: Worked with "data/cg_organic.parquet" containing telemetry data from 30,000 Space Pirates gamers.
- **Exploratory Analytics**:
  - Calculated organic conversion probabilities to the Zalon campaign.
  - Generated and analyzed descriptive statistics to identify characteristics of numeric and categorical data.
  - Created histograms for numeric variables and frequency plots for categorical variables to assess data distribution.

## Predictive Modeling
- **Model Training**:
  - Employed logistic regression, training the model with a 'training' flag to separate training and testing data.
  - Explored key features that influence the purchase likelihood of the Zalon campaign.
- **Model Evaluation**:
  - Generated gains curves for both the training and testing datasets.
  - Evaluated model performance using the Area Under the Curve (AUC) metric.

## Ad-Experiment Analysis
- **Setup**:
  - Executed an ad-experiment with 180,000 customers divided into three groups to assess the impact of in-app ads and predictive modeling.
- **Group Analysis**:
  - Measured conversion rates and profits for the groups exposed to no ads, random ads, and targeted ads based on predictive modeling.
  - Analyzed the effectiveness of ad campaigns and the predictive model on conversion rates and profitability.

## Model Retraining and Evaluation
- **Retraining**:
  - Updated the logistic regression model with new data from ad-exposed customers to integrate recent insights.
- **Performance Comparison**:
  - Compared the performance of the original and retrained models using AUC and gains curves, highlighting improvements.

## Advanced Predictive Techniques
- **Techniques Used**:
  - Applied neural networks and random forests to enhance prediction accuracy.
- **Evaluation**:
  - Assessed and compared the performance of these models against the logistic regression model, focusing on prediction accuracy and profitability.

## Key Accomplishments
- **Effective Predictive Model Development**:
  - Created robust models that accurately predict customer purchasing behavior, aiding Creative Gaming in optimizing marketing strategies.
- **Insights from Data Analytics**:
  - Provided comprehensive insights into player behavior and promotional strategy effectiveness, supporting data-driven decision making.
- **Enhancement of Marketing Efficiency**:
  - Showcased the significant impact of targeted advertising based on predictive analytics on improving conversion rates and profits, thereby maximizing marketing ROI.

## Technologies and Tools Used
- **Data Analysis and Modeling**: Python, pandas, pyrsm, logistic regression, neural networks, random forests.
- **Data Visualization**: Utilized Matplotlib for creating histograms and gains curves.
- **Version Control and Collaboration**: Managed code and collaborated with team members using Git and GitHub.
