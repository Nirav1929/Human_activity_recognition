# activity_recognition
We propose a CNN LSTM architec- ture to predict human activity based on the data gathered from wearable sensors. We have used Convolutional Neural Net- work (CNN) layers for feature extraction and recurrent neural network architecture LSTM for activity recognition. In the first phase of the project, we compared performance of classical machine learning methods where we did not use sequentiality property of the time series dataset. Recurrent Neural Networks are the state of the art algorithm for sequential data. After comparing different RNN models, model with CNN LSTM has given the best results for the test dataset.
After sampling the training dataset as mentioned in section III-B, we perform undersampling as mentioned in III-D to counter class imbalance. The input sequence is fed to cnn to learn characteristic features of the time-series data. These extracted features are later fed into LSTM model to map the internal representation of time series data to activity type. Below figure summarizes our final model.



 