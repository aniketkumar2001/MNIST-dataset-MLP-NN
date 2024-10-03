# MNIST-dataset-MLP-NN
Training an MLP Neural Network for MNIST Dataset using only numpy and pandas


The dataset can be downloaded in CSV format from the following link: [MNIST Datasets](https://git-disl.github.io/GTDLBench/datasets/mnist_datasets/).
I implemented two neural network models: the first with two hidden layers of 16 neurons each, and the second with three hidden layers containing 56, 16, and 16 neurons. 
The ReLU activation function is used for the hidden layers, while the sigmoid activation function is applied to the output layer.

The two-hidden-layer model achieved an accuracy of 86%, while the three-hidden-layer model reached 96% on the test dataset, with the corresponding confusion matrix plotted for performance visualization. 
The weights and biases of both trained models have been saved in .npy format and are provided in zip files named WB_2HL and WB_3HL.
