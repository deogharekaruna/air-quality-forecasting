# air-quality-forecasting
Air Quality Forecasting using Time Series and Prophet
📌 Project Overview
Air pollution is one of the most critical environmental challenges affecting public health worldwide. This project focuses on predicting air quality trends using time-series forecasting techniques.
Using the AirQualityUCI dataset, a machine learning pipeline was developed to preprocess environmental sensor data and forecast future air quality levels.

📊 Project Workflow

1. Data Collection
AirQualityUCI dataset containing atmospheric sensor measurements.

2. Data Cleaning
Removed redundant columns.
Converted invalid sensor values (-200) into missing values.
Applied mean imputation to handle missing data.

3. Exploratory Data Analysis
Analyzed distributions of environmental variables.
Visualized correlations between pollutants and atmospheric factors.

4. Feature Engineering
Combined date and time columns into a unified datetime feature.
Prepared the dataset for time-series modeling.

5. Time Series Forecasting
Implemented Facebook Prophet model.
Captured trend and seasonality patterns in air quality indicators.
Generated predictions for 365 future hours.

📈 Model Output
The model provides:
Future air quality forecasts
Seasonal patterns
Trend analysis
Prediction confidence intervals

🛠 Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Facebook Prophet
Google Colab

🚀 Future Enhancements
Implement LSTM / Deep Learning models for improved forecasting accuracy
Integrate real-time air pollution APIs
Deploy as a web dashboard using Streamlit
