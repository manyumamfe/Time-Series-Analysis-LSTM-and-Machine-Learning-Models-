# Time-Series-Analysis-LSTM-and-Machine-Learning-Models-


This notebook focuses on forecasting hourly energy consumption for the PJM region using a combination of time series analysis, Long Short-Term Memory (LSTM) networks, and other machine learning techniques. It starts with an introduction to various types of time series data, such as univariate vs. multivariate, stationary vs. non-stationary, and seasonal vs. non-seasonal, and provides visual demonstrations to understand these categories better.

The notebook then loads the PJM Hourly Energy Consumption dataset, which contains historical hourly energy usage data. It includes steps for data preprocessing, such as handling missing values, setting the datetime index, and visualizing trends, seasonality, and patterns in energy consumption.

After preprocessing, the notebook applies a range of modeling techniques to forecast future energy consumption. It includes traditional statistical models like ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) to capture linear relationships in the data. Additionally, advanced machine learning models, such as XGBoost, and deep learning models, such as LSTM (Long Short-Term Memory), are implemented to leverage their ability to capture complex, non-linear patterns in the time series data.

The notebook guides through model training, hyperparameter tuning, and evaluation using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE). It demonstrates how integrating LSTM neural networks, known for their effectiveness in sequence prediction problems, enhances the forecast accuracy in energy management.
