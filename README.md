Goal: Forecasting Sensor Measurements in Smart Air Aquality Monitoring System Temporal forecasting of temperature(T) and Carbon Monoxide (CO) sensor data one day ahead

Attributes to consider : 1) CO 2) T

Inorder to forecast T you should only use T and similarly for ‘CO’ making it a univariate time series problem.

Observation : The given data is a Continuous Time series Data containing 24 data points per day. The data extends to 14 days. The Following are the Data Graph Representations

Given a procedure: predict the 8th day using past 7 days information calculate the MAPE predict the 9th day by updating the training database from the 8th day values given now calculate the MAPE similarly go on till last day in test set

Models Used: Dense Neural Network Multiple layers of Bidirectional LSTM 1D Convolution Networks Hybrid model with combinations of LSTM’s and 1D cone’s TBATS NBEATS
