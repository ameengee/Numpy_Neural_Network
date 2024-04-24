# NUMPY NEURAL NETWORK

In this repository, I implemented a simple neural network to perform handwritten digit recognition on the MNIST dataset using only numpy matrices as an instructional example to better understand the inner workings of neural networks.

# Dependencies

- numpy
- pandas (for reading data only)
- matplotlib (for visualizing results)
- time

### requires MNIST dataset
- can be downloaded here: https://git-disl.github.io/GTDLBench/datasets/mnist_datasets/

# Usage

3 major ipynb files available in this repository:
- **Numpy_AI_2_layers**: basic AI with 1 input layer, 1 hidden layer, and 1 output layer (784, 16, 10). Defines each weight, bias, and neuron matrix individually as numpy arrays, and performs calculations one at a time.
- **Numpy_AI_lists**: AI with 1 input layer, 2 hidden layers, and 1 output layer (784, 16, 16, 10). Defines weight, bias, and neuron matrices individually, but stores the matrices in a list of matrices. Performs the same calculations by indexing the lists directly.
- **Numpy_generalized_AI**: Allows for the user to input however many layers they want (784, ..., 10). Defines weight, bias, and neuron matrices with for loops and indexing, and stores the matrices in a list of matrices. Performs the calculations by indexing the lists using loops.

# Licence

Liscenced with GPL-3.0 license
