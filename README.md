# Drowsy-Driver-Detection

Project Summary - 

1. Trained a recurrent neural network based on the outputs of a real time eye tracking model in videos using Haar Cascades and Can Shift algorithm. 
2. Used significant features from the final pooling layer to stitch as sequence of feature vectors for next frames
3. This sequence (2048-D) was given as input to the Long Short Term Memory (LSTM) Recurrent Neural Networks (RNN) which predicted te drowsiness of the driver given the video sequence and sounds an alarm in such a case
4. Improved network weights (hyper parameter tuning) by Adam Optimization algorithm to result in 87% prediction accuracy
