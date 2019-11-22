
# First Neural Network - Udacity Deep Learning Nanodegree

### Introduction
---
#### In this project, you'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher level tools such as Tensorflow. You'll also get to see how to apply these networks to solve real prediction problems!

#### The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

### Instructions
---
#### Download the project materials from our GitHub repository. You can get download the repository with git clone https://github.com/udacity/deep-learning.git. Our files in the GitHub repo are the most up to date, so it's the best place to get the project files.
```cd into the first-neural-network directory```.
#### Download anaconda or miniconda based on the instructions in the Anaconda lesson.
#### Create a new conda environment:
```conda create --name dlnd python=3```
#### Enter your new environment:
Mac/Linux: >> ```source activate dlnd```
Windows: >> ```activate dlnd```

#### Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
```conda install numpy matplotlib pandas jupyter notebook```

#### Run the following to open up the notebook server:
```jupyter notebook```

#### In your browser, open Your_first_neural_network.ipynb
#### Follow the instructions in the notebook; they will lead you through the project. You'll ultimately be editing the my_answers.py python file, whose components are imported into the notebook at various places.
#### Ensure you've passed the unit tests in the notebook and have taken a look at the rubric before you submit the project!If you need help running the notebook file, check out the Jupyter notebook lesson.

## Project description
---
#### The objective of this study is to develop a deep learning model that will predict from historical data that how many bike you will need in a near future. It is a project based on daily bike rental ship. The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activatio function is ```f(x) = x```. A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights.

### Accuracy Value
---
**1)Training Loss 0.056**
**2)Validation Loss 0.145**
