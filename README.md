# NumpyMultilayerPerceptron

This implementation of a Multilayer Perceptron network was written in Python using only Numpy. The network can process any input represented as an array. Here, the performance of this implementation is checked using the MNIST and Fashion-MNIST dataset. The weights and biases of the network are optimized using the simplest form of stochastic gradient descent.

The network takes the following parameters for training `learning_rate`, `batch_size`, `epochs`. The network's architecture (depth and width) is defined by `layer_size` which represents a list of integers. Here, the following training parameters are used:

```python
# Training parameters
learning_rate = 0.1
batch_size = 64
epochs = 100

# Network architecture
layer_size = [n_input, 128, 128, 128, n_classes]
````

