LSTM Modeling || Feature Engineering || Deep Learning
# Air Pollution Forecasting

This repository contains a machine learning project on **Air Pollution Forecasting**, where models are trained to predict future air pollution levels based on historical environmental data.

## Project Overview
Air pollution forecasting is a crucial task for urban planning and public health. This project uses time series forecasting techniques to predict air pollution levels (such as PM2.5) based on weather conditions and previous pollution data.

## Dataset
The dataset used in this project is provided in two CSV files:
- `LSTM-Multivariate_pollution.csv`: Contains historical data with various environmental features.
- `pollution_test_data1.csv`: A separate dataset for testing the model's performance.

### Features in the Dataset
- **Date/Time**: Timestamp of the observation.
- **PM2.5**: Particulate matter concentration.
- **Dew Point**: Dew point temperature.
- **Temperature**: Ambient temperature.
- **Pressure**: Atmospheric pressure.
- **Wind Speed**: Wind speed.
- **Precipitation**: Amount of precipitation.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd air-pollution-forecasting
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Air_Pollution_Forecasting.ipynb
   ```
4. Follow the instructions in the notebook to preprocess the data, train the model, and evaluate its performance.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TensorFlow/Keras

## Methodology
1. **Data Preprocessing**:
   - Handling missing values.
   - Normalizing the data.
   - Creating lag features for time series forecasting.

2. **Model Training**:
   - An LSTM (Long Short-Term Memory) neural network is used for forecasting.
   - The model is trained on historical pollution and weather data.

3. **Evaluation**:
   - The model's predictions are evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Results
The notebook provides:
- Predicted vs actual air pollution levels.
- Visualizations of model performance.

## Future Improvements
- Experiment with other time series models such as ARIMA or Prophet.
- Incorporate additional features like traffic data or industrial activity.
- Deploy the model as a web application for real-time forecasting.
