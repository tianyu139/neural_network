## Implementation of neural network methods in Python from scratch

---

#### Classification problem using iris dataset from sklearn

-  Loss function: MSE/ Quadratic loss function
-  Activation function: tanh
-  Methods used:
  - Gradient descent using backpropagation (Iris Dataset)
  - Stochastic gradient descent using backpropagation (MNIST Datset)

#### Data set used:

Dataset obtained from:
1. MNIST Dataset obtained from http://yann.lecun.com/exdb/mnist/
2. Sklearn Iris dataset

### Improvements that can be made:
1. Shuffle MNIST training data before training
2. Running for more iterations (currently running for 5)
3. Train network more times to optimise for convergence to global minimum from random initialization of weights
4. Tuning of hyperparameters

### Credits:
1. https://gist.github.com/craffel/2d727968c3aaebd10359 for code to visualize neural network
2. Sources of dataset as listed above
3. python-mnist https://github.com/sorki/python-mnist for parsing of MNIST dataset
