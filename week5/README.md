# Lab Exercise: Backpropagation in a Neural Network

## Objective
- To implement and analyze backpropagation in a simple neural network.
- To understand how weights are updated and how error convergence occurs over multiple iterations.
- To visualize the learning process using graphs.

---

## Problem Statement
You are given a feedforward neural network with the following specifications (use the initial values for input weights and biases discussed in class):
- **Input Layer:** 3 neurons
- **Hidden Layer:** 2 neurons (Sigmoid activation)
- **Output Layer:** 1 neuron (Sigmoid activation)
- **Target Output:** 1
- **Learning Rate:** Experiment with values 0.01, 0.1, and 0.5.

**Task:** Implement backpropagation, train the network for 1000 iterations, and analyze how weights and errors change over time.

---

## Tasks

### 1. Initialize the Neural Network
- Define the structure of the network.
- Initialize weights and biases with random values.

### 2. Implement Forward Propagation
- Compute the activations for the hidden and output layers using the sigmoid activation function.

### 3. Compute Error
- Use a suitable error function (e.g., Mean Squared Error) to calculate the difference between the predicted and target output.

### 4. Perform Backpropagation
- Calculate gradients using the chain rule.
- Update weights and biases using the computed gradients.

### 5. Run Multiple Iterations
- Repeat forward and backward propagation for **1000 iterations**.
- Record how the error decreases over time.

---

## Analysis and Visualization Tasks

### 1. Error vs. Iterations Graph (Required)
- **Plot:** Number of iterations (X-axis) vs. Error (Y-axis).
- **Observation:**
  - Does the error decrease gradually?
  - Does it oscillate due to an improper learning rate?

### 2. Weight Updates Over Iterations
- **Plot:** Number of iterations (X-axis) vs. Selected weight value (Y-axis).
- **Observation:**
  - Do weights stabilize over time?
  - Do they oscillate due to a large learning rate?

### 3. Learning Rate Comparison (Recommended)
- **Plot:** Error vs. Iterations for learning rates 0.01, 0.1, and 0.5 (all on the same graph).
- **Observation:**
  - Which learning rate achieves faster convergence?
  - Does a high learning rate cause oscillations?

### 4. Decision Boundary Visualization
- Visualize the decision boundary before and after training.

---

## Additional Task
- Modify the network to use **ReLU activation** instead of sigmoid and compare its performance.
