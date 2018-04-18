# Convolutional Neural-Network
<hr>
An implementation of Convolutional Neural-Network (CNN) for MNIST dataset with various techniques such as Dropout, MaxPooling etc.., using Keras

## Network Architecture
<hr>
CNN with 4 layers has following architecture<br>

* Input layer: 784 nodes (MNIST image size)

* 1st convolution layer: 32x3x3
* 2nd convolution layer: 32x3x3
	* MaxPooling layer
	* Dense layer
* 3rd Fully connected layer: 1024 nodes
* Outpul layer: 10 nodes (number of class for MNIST)

## Simulation Results
<hr>
CNN with the same hyper-parameters gives the following results:

* A single model: **98.95%** of accuracy<br>
	(The model is saved in `mnist_cnn_trained.h5`)
	
* Model Loss: **0.034%**