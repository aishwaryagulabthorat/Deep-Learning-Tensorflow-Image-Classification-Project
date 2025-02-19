**MNIST Digit Classification Project**


**Overview**
This project implements neural network models for both binary and multi-class classification using the MNIST digit dataset. It includes two main components:

Binary Classification (Digits 7 vs 9)

Multi-class Classification (All 10 digits)

**Features**

Binary classification with different weight initializers (Normal, He, Xavier) and activation functions (ReLU, Sigmoid, Tanh)

Multi-class classification using optimal architecture

Comprehensive performance analysis including:

Confusion matrices

Learning curves

Classification reports

Visual prediction examples

**Requirements**

tensorflow

numpy

scikit-learn

matplotlib

seaborn

pandas

**Results**

**Binary Classification**

Implements 9 different combinations of weight initializers and activation functions

Provides comparative analysis of different configurations

Includes confusion matrices and learning curves for each combination

**Multi-class Classification**

Achieves high accuracy across all 10 digit classes

Provides detailed per-class performance metrics

Includes visualization of model predictions

**Model Architecture**
**Binary Classification**

Input Layer: Flattened 28x28 images

Hidden Layer 1: 128 neurons with dropout

Hidden Layer 2: 64 neurons with dropout

Output Layer: 1 neuron (sigmoid activation)

**Multi-class Classification**

Input Layer: Flattened 28x28 images

Hidden Layer 1: 256 neurons with dropout

Hidden Layer 2: 128 neurons with dropout

Output Layer: 10 neurons (softmax activation)


**Acknowledgments**

MNIST Dataset: http://yann.lecun.com/exdb/mnist/

TensorFlow Documentation: https://www.tensorflow.org/

