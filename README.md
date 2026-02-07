Seasonal Energy Consumption Forecasting Using SARIMA & SARIMAX
📌 Project Overview

Accurate forecasting of electricity consumption is essential for power distribution companies to ensure reliable supply, prevent outages, and optimize energy distribution. Electricity demand data exhibits strong seasonal patterns and is influenced by external factors such as temperature.

This project implements SARIMA and SARIMAX time series models to forecast monthly electricity consumption. SARIMA captures seasonal patterns, while SARIMAX improves forecasting accuracy by incorporating temperature as an exogenous variable.

🎯 Objectives

Analyze historical electricity consumption data

Identify trends and seasonal patterns

Build and compare SARIMA and SARIMAX models

Incorporate temperature as an external influencing factor

Evaluate model performance using standard metrics

Generate future electricity consumption forecasts

📊 Dataset Description

The dataset contains monthly records with the following attributes:

Date – Monthly timestamp

Electricity Consumption – Energy usage values

Temperature – Average monthly temperature

The data is preprocessed to handle missing values and ensure time series compatibility.

🧠 Methodology

Data collection and preprocessing

Exploratory data analysis (trend & seasonality)

Seasonal decomposition

Parameter selection using ACF and PACF

SARIMA model development

SARIMAX model development with temperature

Model evaluation and residual diagnostics

Forecasting and result comparison

🧮 Models Used
SARIMA

Captures seasonal and non-seasonal patterns

Suitable for time series with strong periodic behavior

SARIMAX

Extends SARIMA by adding exogenous variables

Models real-world influence of temperature on energy demand

Provides improved forecast accuracy

📈 Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Lower values indicate better model performance.

📉 Results

SARIMA successfully captured seasonal patterns

SARIMAX outperformed SARIMA by incorporating temperature

Residual diagnostics confirmed model validity

SARIMAX produced more realistic and accurate forecasts

🛠️ Tools & Technologies

Python

Pandas

Statsmodels

Matplotlib

Scikit-learn

📂 Project Structure
├── data/
│   └── energy_consumption.csv
├── notebooks/
│   └── sarima_sarimax_forecasting.ipynb
├── images/
│   └── plots_and_flowchart.png
├── report/
│   └── SARIMAX_Energy_Forecasting_Report.pdf
├── README.md

▶️ How to Run

Install required libraries:

pip install pandas numpy matplotlib statsmodels scikit-learn


Place the dataset in the data/ folder

Run the Jupyter notebook step by step

View plots, evaluation metrics, and forecasts

🚀 Future Enhancements

Add more exogenous variables (holidays, humidity, economic data)

Perform hyperparameter tuning

Compare with machine learning and deep learning models

Deploy as a web application using Flask or Streamlit
