# Neural-Networks-for-Binary-Classification
In this hands-on assignment, I built a neural network using Tensorflow to recognize handwritten digits from the MNIST dataset. To deepen my understanding I implemented the network's forward path in NumPy, revealing the inner workings of machine learning frameworks.

# Deep Learning Specialization - Week 1 Assignment: Building Blocks of Deep Neural Networks

This project contains my implementation of foundational neural network components using **NumPy** and **TensorFlow/Keras**, as part of the **Deep Learning Specialization** by Andrew Ng on Coursera.

## 📘 Overview

In this assignment, I built essential building blocks for neural networks from scratch and also using the Keras API. The focus was on understanding:
- The structure and parameters of dense (fully connected) layers
- The process of forward propagation for both single and multiple input examples
- Vectorized implementations of neural network computations

## 🧠 What I Implemented

### ✅ Exercise 1: Constructing a Sequential Model with Keras
- Built a feedforward neural network with:
  - Input layer: 400 features
  - Hidden layers: 25 units and 15 units (sigmoid activation)
  - Output layer: 1 unit (sigmoid activation)

### ✅ Exercise 2: Manual Dense Layer (Single Example)
- Created a function `my_dense()` that:
  - Computes the dot product of inputs and weights
  - Adds a bias term
  - Applies a given activation function
  - Handles one example at a time (non-vectorized)

### ✅ Exercise 3: Vectorized Dense Layer (Multiple Examples)
- Built `my_dense_v()` to:
  - Apply the dense layer computation using matrix multiplication (`np.matmul`)
  - Efficiently handle batches of input data

## 🛠️ Skills Used & Learned

- **Machine Learning Fundamentals**:
  - Structure of neural networks
  - Forward propagation
  - Importance of vectorization for performance

- **Programming Concepts**:
  - NumPy for mathematical operations
  - TensorFlow/Keras for model construction
  - Clean code organization in Jupyter Notebooks

- **Mathematical Foundations**:
  - Dot products and matrix multiplication
  - Sigmoid activation function
  - Shapes of weight matrices and outputs

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/deep-learning-week1.git
   cd deep-learning-week1
jupyter notebook C2_W1_Assignment.ipynb
#Sample Output
[[0.54735762 0.57932425 0.61063923]
 [0.57199613 0.61301418 0.65248946]
 [0.5962827  0.64565631 0.6921095 ]
 [0.62010643 0.67699586 0.72908792]]

📚 Acknowledgments
This project is part of the Deep Learning Specialization by Andrew Ng on Coursera. Special thanks to DeepLearning.AI for providing world-class ML content.
