# Neural-Network-Classifier-for-MNIST-dataset
MNIST is a standard digit classification dataset. Given a 28 × 28 image containing a digit from 0 to 9, our goal is deducing which digit the image corresponds to. The dataset has 50,000 training and 10,000 test examples. 

**Neural Network Classifier for MNIST (From Scratch)**

**Project Description**
Unlike a basic linear classifier, this model utilizes a hidden layer to capture non-linear relationships within the data.

**Key Technical Implementations**

**Layer Structure**: Designed with an input layer (784 neurons), a hidden layer (flexible size), and an output layer (10 neurons for digit classes).

**Manual Backpropagation**: Implemented the chain rule from scratch to calculate gradients for both output and hidden layer weights.

**Activation Functions**: Integrated ReLU (Rectified Linear Unit) for the hidden layer to introduce non-linearity and mitigate the vanishing gradient problem.

**Optimization**: Utilized Minibatch Stochastic Gradient Descent (SGD) with L2 regularization to prevent overfitting.

**Tech Stack**

Language: Python

Core Libraries: NumPy (Linear Algebra), Matplotlib (Visualization)

Verification: PyTorch, Torchvision

**Results**

Dataset Size Experiments: Demonstrated that increasing the training set size from N=100 to N=10,000 significantly improves generalization and reduces overfitting.

**How to Use**

1.Clone the repository.

2.Install dependencies: pip install numpy torch torchvision matplotlib.

3.Run the Jupyter Notebook Neural Network Classifier_codes_Thi_Thi_Khine-updated.ipynb to replicate the experiments and plots.


