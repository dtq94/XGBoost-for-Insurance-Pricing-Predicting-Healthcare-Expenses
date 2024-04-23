# Insurance Pricing Forecast Using XGBoost Regressor

## Project Overview
Insurance companies aim to cover policyholders' expenses incurred from damages to health or property by offering various policies such as medical, house, motor vehicle, and fire insurance. Premium calculation traditionally involves time-consuming human labor and complex interactions in data. This project focuses on building a machine learning model, specifically an XGBoost Regressor, to forecast healthcare expenses based on features like age, BMI, smoking status, etc. The goal is to establish rates that maintain profitability for the insurance firm.

## Aim
The aim of this data science project is to build and evaluate linear and XGBoost regression models to predict healthcare charges for each customer. This analysis assists the insurance firm in devising premium plans to maximize profits.

## Data Description
The insurance price forecast dataset contains historical records for 1338 insured customers. Column definitions:
- **age**: Age of the primary beneficiary.
- **sex**: Gender of the primary beneficiary.
- **BMI**: Body mass index of primary beneficiary.
- **children**: Number of children the primary beneficiary has.
- **smoker**: Whether the primary beneficiary smokes.
- **region**: Residential area of the primary beneficiary in the US.
- **charges**: Individual medical costs billed by health insurance.

## Tech Stack
- **Language**: Python
- **Libraries**: pandas, numpy, matplotlib, plotly, statsmodels, sklearn, xgboost, skopt

## Approach
1. **Exploratory Data Analysis (EDA)**:
   - Distributions
   - Univariate Analysis
   - Bivariate Analysis
   - Correlation (Pearson, Chi-squared Tests, ANOVA)
2. **Build and Evaluate Baseline Linear Model**:
   - Linear regression assumptions
   - Data preprocessing
   - Model training and evaluation (RMSE)
3. **Improve on Baseline Linear Model**:
   - Introduction to non-linear model (XGBoost)
   - Data preprocessing
   - Using Sklearn's `Pipeline` to optimize model training
   - Model evaluation (RMSE)
   - Comparison to baseline model
4. **Presenting Results to Non-Technical Stakeholders**

## Project Structure
```
|-- InputFiles
    -- insurance_data.csv
|-- SourceFolder
    |-- ML_Pipeline
        -- eda.py
        -- model_performance.py
        -- stats.py
    |-- Engine.py

