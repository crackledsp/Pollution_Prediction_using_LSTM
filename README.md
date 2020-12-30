# Pollution_Prediction
Based on history of air pollution, predict pollution for next day
Use 3 months of history to predict the next day.

DataSet
temp_avr,temp_max,temp_min,pres,u,v,prec,datetime are the columns of the dataset and observations of the city Budateteny.
Used Window size of 3 months to predict the future pollution for the city.

**LSTM (Long Short-Term Memory)** is one of the Recurrent Neural Network (RNN) architecture used in Deep Learning.

Keras is an open-source Python Deep Learning library, that could be running on Tensorflow back-end.

Architecture
- TimeseriesGenerator (Window Size : 90)
- LSTM Layer
- Dense (activation function using LeakyRelu)
- Optimizer: Adam, Loss Function: Mean Squared Error
