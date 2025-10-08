#  MNIST Neural Network — Pure NumPy Implementation

This project is a **simple neural network built from scratch in Python using only NumPy**, trained on the **MNIST handwritten digits** dataset (0–9).  
It demonstrates the fundamentals of forward propagation, backpropagation, dropout, and softmax output without relying on high-level frameworks like TensorFlow or PyTorch.

---

##  Project Description

- Dataset: **MNIST** (handwritten digits)
- Hidden layer: 1 layer with `tanh` activation
- Output layer: Softmax (for 10 digits)
- Optimization: Manual gradient descent
- Dropout: Randomly disables neurons during training for better generalization
- Batch training with mini-batches of 100 images

---

##  Technologies Used

- **Python 3.10+**
- **NumPy**
- **Keras (for dataset loading only)**

---

##  Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mnist-numpy.git
   cd mnist-numpy
