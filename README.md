# Prediction-of-lung-cancer-using-CNN
Prediction of lung cancer using CNN 


Firstly, Lung CT images are collected initially to classify them as normal or abnormal. These images are in the format of .dat file.
Then data processing is applied to improve the quality of the images. After this training, the testing of the convolutional neural network is done using available database.
Once the cnn is ready backpropogation algorithm is used as follows:

1. Initialize the weights arbitrarily.
2.Present and input vector pattern to the network.
3. By propagating input forward signals evaluate the outputs.
4. For all output phase neurons calculate the desired output.
5.Complete output of the succeeding layer for all other neurons.
6. In accordance to the learning rate change the weight.
7.For certain number of steps or until error is less than a pre-specified value goes to step -2.
