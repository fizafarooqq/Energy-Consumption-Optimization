# Energy-Consumption-Optimization

This project is designed to create a system that uses machine learning and  deep learning techniques to predict the consumption of energy and then reduce it. 

The project used the UCI Household Power Consumption dataset, which contains over one million one minute readings from a single home in France collected between December 2006 and December 2008. After cleaning the data, the dataset had 953,182 records with an average power consumption of 0.877 kW and a peak consumption hour at 21:00. 

Five different forecasting models were built and compared: a Naive Baseline, Linear Regression, ARIMA, SARIMAX, and an LSTM neural network. The LSTM model gave the best results with an MAE of 0.2735 kW and RMSE of 0.4108 kW. A demand-shaving strategy was then applied to the LSTM predictions, which reduced total energy usage by 4.13%, saving 117.76 kWh over the test period. 

The project shows that deep learning, specifically LSTM, is the most effective approach for predicting household energy use. The system is practical, easy to understand, and could be applied to real smart home systems to help reduce electricity bills and lower carbon emissions.
