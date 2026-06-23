# EV Charging Demand Prediction and Smart City Analytics

## Project Description

This project analyzes Electric Vehicle (EV) charging patterns to understand charging behavior, energy consumption, charger utilization, and city-wise demand trends. The project combines data cleaning, exploratory data analysis (EDA), machine learning, and Power BI dashboarding to generate actionable insights for smart city planning and EV infrastructure development.

---

## Problem Statement

As EV adoption continues to grow, cities need efficient charging infrastructure to meet increasing demand. Understanding charging behavior, peak usage periods, charger preferences, and energy consumption patterns is essential for optimizing charging station placement and resource allocation.

This project aims to analyze EV charging data and develop a predictive model to estimate energy consumption while providing business insights through an interactive dashboard.

---

## Data Source

* Dataset: EV Charging Patterns Dataset
* Format: CSV
* Records: 1,320+
* Features:

  * Vehicle Model
  * Battery Capacity
  * Charging Duration
  * Charging Rate
  * Charging Cost
  * Charging Station Location
  * Charger Type
  * User Type
  * Temperature
  * Distance Driven
  * State of Charge

---

## Methodology

### 1. Data Cleaning

* Handled missing values
* Converted date and time columns
* Created new features:

  * Hour
  * Month
  * Day
  * Weekday
* Prepared a cleaned dataset for analysis

### 2. Exploratory Data Analysis (EDA)

* Energy Consumption by City
* Peak Charging Hours Analysis
* Charger Type Utilization
* Vehicle Model Analysis
* Correlation Analysis
* Business Insight Generation

### 3. Predictive Modeling

* Train-Test Split
* Random Forest Regressor
* Model Evaluation using:

  * Mean Absolute Error (MAE)
  * R² Score

### 4. Dashboard Development

Built an interactive Power BI dashboard featuring:

* KPI Cards
* City-wise Energy Analysis
* Peak Charging Hours
* Charger Type Distribution
* Vehicle Model Analysis
* Interactive Filters and Slicers

---

## Key Findings

1. Los Angeles recorded the highest total energy consumption.
2. Charging demand varies throughout the day, with identifiable peak charging periods.
3. Level 2 chargers contributed the highest share of energy consumption.
4. Tesla Model 3 users consumed the highest amount of charging energy.
5. Correlation analysis showed weak linear relationships among most numerical variables.

---

## Model Results

### Random Forest Regressor

* Mean Absolute Error (MAE): 18.28
* R² Score: -0.026

The model achieved limited predictive performance due to weak correlations among the available features. Future improvements can be achieved through additional feature engineering and larger datasets.

---

## Dashboard Features

* Total Energy Consumed
* Average Charging Cost
* Average Charging Duration
* Total Charging Sessions
* Energy Consumption by City
* Energy Consumption by Vehicle Model
* Energy Consumption by Charger Type
* Peak Charging Hours
* Interactive Slicers

## Conclusion

This project demonstrates how data analytics and machine learning can be used to analyze EV charging behavior and support smart city decision-making. The insights generated can help optimize charging infrastructure, improve user experience, and support sustainable transportation planning.

