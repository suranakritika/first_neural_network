#First Neural Network

#Introduction
The objective of this study is to develop a deep learning model that will predict from historical data that how many bike you will need in a near future. It is a project based on daily bike rental ship.

#Dataset
The complete description of dataset is given on https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset.

#Neural Network
The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is f(x) = x. A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer.
We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights.

#Result
Accuracy	Value
Training Loss	0.056
Validation Loss	0.145

#Ipython notebook
Jupyter/iPython Notebook has been provided to know about the model and its working. https://github.com/suranakritika/first_neural_network/blob/master/Your_first_neural_network.ipynb



