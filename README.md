# Predictive Modeling & Market Analysis: Boston Housing Data

## Project Overview
This project utilizes **Multiple Linear Regression** to analyze and predict asset valuation based on the Boston Housing dataset. The objective was to build a robust statistical model that identifies key cost drivers (independent variables) and accurately forecasts market value (dependent variable).

While applied here to real estate, this methodology—variable selection, assumption testing, and error minimization—is directly transferable to **Supply Chain forecasting**, such as predicting logistics costs or estimating inventory demand based on historical data.

## Key Competencies Demonstrated
* **Statistical Modeling:** Constructed Linear Regression models in **R**.
* **Variable Selection:** Utilized stepwise selection and correlation analysis to isolate statistically significant predictors.
* **Assumption Verification (LCRIM):** Rigorously tested for Linearity, Constant Variance (Homoscedasticity), Randomness, Independence, and Normality of residuals to ensure model validity.
* **Data Cleaning:** Handled missing values and identified outliers using Cook’s Distance to improve prediction accuracy.

## Technical Stack
* **Language:** R
* **Libraries:** `ggplot2` (Visualization), `dplyr` (Data Manipulation), `car` (Regression Diagnostics).
* **Techniques:** OLS Regression, Residual Analysis, Hypothesis Testing.

## Business Use Case: Supply Chain Applicability
In this analysis, we determined how variables like *crime rate* or *distance to employment centers* impact *price*.

In a **Supply Chain Data Specialist** context, this same framework applies to:
* **Freight Cost Modeling:** Using regression to predict shipping rates based on fuel prices, distance, and weight.
* **Demand Forecasting:** Correlating sales data with seasonal trends and economic indicators to optimize inventory levels.
* **Risk Assessment:** Identifying outliers in supplier lead times to predict potential delays.

## Repository Contents
* `analysis.R`: The core R script containing data processing, model generation, and diagnostic plots.
* `boston.csv`: The raw dataset used for training and testing.

---
*Authors: Annie H., Trenton G.*
