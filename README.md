# Seasonal Energy Consumption Forecasting Using SARIMA & SARIMAX

## Project Overview
Accurate electricity demand forecasting is essential for power distribution companies to ensure uninterrupted supply, prevent outages, and optimize energy distribution. Electricity consumption data exhibits strong seasonal patterns and is influenced by external factors such as temperature.

This project implements **SARIMA** and **SARIMAX** models to forecast monthly electricity consumption. SARIMA captures seasonal patterns in the data, while SARIMAX enhances forecasting accuracy by incorporating temperature as an exogenous variable.

---

## Objectives
- Analyze historical electricity consumption data  
- Identify trend and seasonality components  
- Build SARIMA and SARIMAX forecasting models  
- Incorporate temperature as an external influencing factor  
- Compare model performance using evaluation metrics  
- Generate future electricity consumption forecasts  

---

## Dataset
The dataset consists of monthly time series data with the following fields:
- **Date** – Monthly timestamp  
- **Consumption** – Electricity consumption values  
- **Temperature** – Average monthly temperature  

The data is preprocessed to handle missing values and formatted for time series analysis.

---

## Methodology
1. Data loading and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Seasonal decomposition of the time series  
4. Parameter selection using ACF and PACF plots  
5. SARIMA model development  
6. SARIMAX model development with temperature as an exogenous variable  
7. Model evaluation and residual diagnostics  
8. Forecasting and result comparison  

---

## Models Used

### SARIMA
- Captures seasonal and non-seasonal patterns in time series data  
- Suitable for electricity consumption with strong periodic behavior  

### SARIMAX
- Extends SARIMA by including exogenous variables  
- Models the impact of temperature on electricity demand  
- Produces more accurate and realistic forecasts  

---

## Evaluation Metrics
- Mean Absolute Error (MAE)  
- Root Mean Square Error (RMSE)  
- Mean Absolute Percentage Error (MAPE)  

---

## Results
- SARIMA successfully modeled seasonal consumption patterns  
- SARIMAX outperformed SARIMA due to the inclusion of temperature  
- Residual diagnostics confirmed model adequacy  
- SARIMAX provided improved forecast accuracy  

---

## Tools & Technologies
- Python  
- Pandas  
- Statsmodels  
- Matplotlib  
- Scikit-learn  

---

## Project Structure
├── data/
│ └── energy_consumption.csv
├── notebook/
│ └── sarima_sarimax_forecasting.ipynb
├── images/
│ └── plots_and_flowchart.png
├── report/
│ └── SARIMAX_Energy_Forecasting_Report.pdf
├── README.md


## How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib statsmodels scikit-learn
Place the dataset in the data/ directory

Open and run the Jupyter notebook step by step

View plots, evaluation metrics, and forecasts

Future Scope
Add more exogenous variables such as holidays or humidity

Perform hyperparameter tuning

Compare with machine learning and deep learning models

Deploy the model as a web application


