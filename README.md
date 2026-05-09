# EV-CHARGING-STATION-LOAD-FORCASTING
# EV Charging Demand Forecasting using Time-Series, Machine Learning & Deep Learning

## Project Overview

The rapid growth of Electric Vehicles (EVs) is increasing pressure on power grids due to highly variable and time-dependent charging demand. Accurate forecasting of EV charging energy consumption is essential for smart grid planning, load balancing, and efficient charging infrastructure management.

This project presents a comprehensive comparative analysis of:
- Classical Time-Series Models
- Machine Learning Models
- Deep Learning Models

for predicting EV charging energy demand using real-world datasets.

------------------------------------------------------------

## Objectives

- Analyze EV charging behavior using real-world datasets
- Perform Exploratory Data Analysis (EDA)
- Forecast EV charging demand
- Compare statistical, ML, and DL models
- Evaluate model performance on clean and noisy datasets
- Identify the most robust forecasting approach

------------------------------------------------------------

## Datasets Used

1. Boulder EV Charging Dataset
2. Session EV Charging Dataset

------------------------------------------------------------

## Features Used

- Charging Start Time
- Charging End Time
- Total Duration
- Charging Time
- Energy Consumed (kWh)
- Plug Type
- Battery Capacity
- State of Charge (SOC)
- Time-based Features (Hour, Day, Month)

------------------------------------------------------------

## Methodology

1. Data Collection
2. Data Preprocessing
   - Missing value handling
   - Duplicate removal
   - Outlier removal using IQR
   - Data transformation
   - Feature engineering

3. Exploratory Data Analysis (EDA)
   - Correlation analysis
   - Hourly energy analysis
   - SOC vs Energy analysis
   - Plug type analysis
   - Idle time analysis

4. Model Training

Time-Series Models:
- ARMA
- ARIMA
- Hybrid-ARIMA

Machine Learning Models:
- Linear Regression
- Random Forest

Deep Learning Model:
- LSTM (Long Short-Term Memory)

5. Model Evaluation
- MSE
- RMSE
- R² Score
- Residual Analysis

------------------------------------------------------------

## Why LSTM Performed Best

EV charging data is:
- Nonlinear
- Time-dependent
- Noisy

LSTM effectively captures:
- Temporal dependencies
- Long-term patterns
- Nonlinear relationships

making it the most accurate and robust model for EV demand forecasting.

------------------------------------------------------------

## Key Results

- ARIMA performed poorly on noisy real-world data
- Hybrid-ARIMA improved forecasting accuracy
- Random Forest showed moderate robustness
- LSTM achieved the best performance with highest R² and lowest RMSE

------------------------------------------------------------

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- TensorFlow / Keras
- Jupyter Notebook

------------------------------------------------------------

## Project Workflow

Data Collection
      ↓
Data Preprocessing
      ↓
EDA & Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation

------------------------------------------------------------

## Visualizations Included

- Actual vs Predicted Graphs
- Residual Plots
- ACF/PACF Plots
- SOC vs Energy Analysis
- Hourly Energy Trends
- Plug Type Distribution
- Model Comparison Graphs

------------------------------------------------------------
## Conclusion

This project demonstrates that traditional statistical models struggle with noisy real-world EV charging data, while deep learning approaches—especially LSTM—provide significantly better forecasting accuracy by capturing temporal and nonlinear patterns.

------------------------------------------------------------

## Author

Dipdyuti Chakrabarty
EV Charging Demand Forecasting
