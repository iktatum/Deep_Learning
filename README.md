# Deep_Learning
Cryptocurrency Prediction using the Fear and Greed Index and Price

#  Which model has a lower loss?
   The LSTM price prdictor hjad nthe lower loss, at .016 for the Price Predictor  vs .05 for the Fear and Greed Predictor

#  Which model tracks the actual values better over time?
   The LSTM price predictor tracks the actual vs predicted values over time better than the FNG index. This can be seen with embedded plots in the python notebook

#  Which window size works best for the model?
   I attempted the window sizes of 5, 10, and 15. It appears that there is more loss when the window sizes abre too small or too long. in this case the optimal wiondow size is somewhere between 5 and 10, with 5 being the best output for this exercise.
