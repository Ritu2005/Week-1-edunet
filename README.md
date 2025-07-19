# EV Adoption Forecasting using Machine Learning

## Project Overview

This project focuses on predicting the future adoption of Electric Vehicles (EVs) in different regions using historical data.  
The goal is to develop a regression model that can estimate how the number of EVs will grow over time, based on trends in vehicle types, total vehicle population, and regional information like states or counties.

---

## Objective

- Analyze historical electric vehicle data
- Train a machine learning model to forecast future EV counts
- Evaluate the model’s performance using standard metrics

---

## Dataset

The dataset includes:

- Battery Electric Vehicles (BEVs)
- Plug-In Hybrid Electric Vehicles (PHEVs)
- Total Electric Vehicles
- Non-Electric Vehicles
- Total Vehicles
- Regional data such as State and County
- Time-based features such as Date

The data was sourced from Kaggle and includes vehicle registration trends over time.

---

## Workflow

1. **Data Cleaning and Preprocessing**
   - Removed null values
   - Extracted useful time-based features like 'Year' from the 'Date' column
   - Filtered to include only meaningful columns for prediction

2. **Exploratory Data Analysis (EDA)**
   - Plotted trends in EV growth across years
   - Compared regional variations (e.g., by state)
   - Checked correlations among variables

3. **Modeling**
   - Used `RandomForestRegressor` from scikit-learn
   - Trained the model on past data to predict future EV totals

4. **Model Evaluation**
   - Mean Absolute Error (MAE): 14.67
   - Root Mean Squared Error (RMSE): 314.97
   - R² Score: 0.988

---

## Key Results

The model performed very well, with an R² score close to 1, indicating high accuracy in predicting EV counts based on historical trends.  
This could be useful for governments or businesses planning infrastructure like charging stations or forecasting environmental impact.
