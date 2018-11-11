# Heterogenous Human Activity Recognition

## Recognizing the activities of a person from his data from Smartphone sensors such as accelerometer and gyroscope. The various activities recognized are
* Stand
* Sit
* Walk
* Stairs Up
* Stairs Down 
* Bike

The dataset is taken from UCI [Click here ](https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition)

Since the data from sensors is streamed continuous data and being very huge ( 26+ million instances ), It was sampled down to 1/10th.
Long Short Term Memory Networks which is an extension of Recurrent Neural Networks is used as the model for performing Multiclass classification. The training was performed for a definite batch size for 10 epochs with Adam optimizer and Cross entropy as the loss function. The batch size was varied from 16 to 1024 and accuracy was calculated.
<b>The highest accuracy of 76.57% was obtained for the batch size of 256.</b>
