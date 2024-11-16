# HumanMotionPrediction
Script for human motion prediction neural network -
Recurrent Neural Network in Tensorflow. Regression algo -
Hyper parameter optimization -
Self made dataset -
PLease unzip "HyperparameterTuningSettings" to run with this file as it uses the folders to set the hyperparameters automatically for varying parcitipants -
Uses Keras Hyperparemeter tuner in built with Tensorflow

Please note the train_test split function should have shuffle disabled i.e. train_test_split(X, y, test_size=0.2, shuffle=False)
The number of neurons in the input LSTM layer determines the number of consecutive time steps being processed for a single prediction. Keras tuner finds the optimum value between 32 and 256. 
