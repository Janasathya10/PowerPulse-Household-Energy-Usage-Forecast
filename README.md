# PowerPulse: Household Energy Usage Forecast

## Project Overview
PowerPulse is a machine learning project aimed at predicting household energy consumption based on historical data. This project helps households and energy providers gain insights into usage patterns, optimize energy consumption, and improve demand forecasting.

## Problem Statement
Accurate prediction of household energy usage enables:
- Better energy management for households
- Load balancing for energy providers
- Anomaly detection for irregular energy consumption
- Contribution to smart grid initiatives

## Objectives
- Develop a predictive model for household energy usage
- Explore energy consumption patterns
- Provide actionable insights and recommendations

## Skills & Tools
- Data Preprocessing
- Feature Engineering
- Regression Modeling
- Model Evaluation (RMSE, MAE, R²)
- Visualization (Matplotlib, Seaborn)
- Python, Pandas, Scikit-learn

## Dataset
Individual household electric power consumption dataset from UCI Machine Learning Repository.
https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

## Project Workflow
1. **Data Loading & Exploration**: Understanding dataset structure and quality
2. **Data Preprocessing**: Handling missing values, combining date and time
3. **Feature Engineering**: Creating hour, day of week, and month features
4. **Exploratory Data Analysis (EDA)**: Visualizing consumption trends
5. **Model Building**: Linear Regression & Random Forest
6. **Model Evaluation**: Using RMSE, MAE, R² to assess performance
7. **Feature Importance Analysis**: Identifying key predictors
8. **Prediction Visualization**: Comparing actual vs predicted

## 📈 Key Insights
- Energy consumption peaks between 6 PM and 10 PM
- Hour of the day is the most important factor for predicting usage

## 📝 Recommendations
- Shift high-energy tasks to off-peak hours to save costs
- Energy providers can use similar models for demand forecasting

## 📂 Files
- `PowerPulse_Household_Energy_Usage_Project.ipynb`: Jupyter Notebook with full code and analysis
- `README.md`: Project documentation

## How to Run
1. Clone the repo
2. Install required libraries: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open the notebook in Jupyter and run all cells

---
