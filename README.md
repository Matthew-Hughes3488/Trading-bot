The code for the creation of the DNN model can be found in the DNN.ipynb

To connect the trading bot to the broker all the code in the DNN.ipynb files bellow the text that says "Connecting the trading bot to the broker and setting the trading conditions". The lenght of time the bot will trade for can be modified using the stop value in the final python box. It will stop trading when the market has moved the specified number of ticks. Information about the trades the bot took can be seen by adding the line trader.data() to a new python box in the notebook

If you want to see the code for approach one. Look at the files MLBacktester.ipybn, MLBacktester.py and prediction_algorithm,ipybn files

Required libiarys:
pandas
numpy
matplotlib
keras
pickle
v20
tensorflow
sklearn