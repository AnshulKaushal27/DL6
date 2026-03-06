# Handwritten Digit Classification using Backpropagation

This project implements a **neural network from scratch using Python and NumPy** to classify handwritten digits. The model is trained using the **backpropagation algorithm** and evaluated on the digits dataset.

The goal is to demonstrate how neural networks learn using **forward propagation, backpropagation, and gradient descent** without using deep learning frameworks.

---

# Dataset

The dataset used is the **Digits Dataset** available in Scikit-learn.

It contains images of handwritten digits from **0 to 9**.

### Dataset Details

- Total Samples: 1797
- Image Size: 8 × 8 pixels
- Features: 64 pixel values per image
- Classes: 10 digits (0–9)

---

# Neural Network Architecture

The neural network consists of three layers:

| Layer | Neurons |
|------|------|
| Input Layer | 64 |
| Hidden Layer | 64 |
| Output Layer | 10 |

### Activation Functions

- **Sigmoid** → Hidden layer
- **Softmax** → Output layer

Softmax converts outputs into probabilities for multi-class classification.

---

# Training Process

The training process includes the following steps:

1. Load and preprocess the dataset
2. Normalize input features using **StandardScaler**
3. Apply **One-Hot Encoding** to labels
4. Initialize weights and biases
5. Perform **Forward Propagation**
6. Compute prediction error
7. Apply **Backpropagation**
8. Update weights using **Gradient Descent**
9. Evaluate the model on test data

---

# Libraries Used

- Python
- NumPy
- Scikit-learn

---

# Model Evaluation

The model performance is evaluated using **classification accuracy**.

Example output:
Classification Accuracy: 0.94


Accuracy may vary slightly depending on training initialization.

---

# How to Run

Install required libraries:

```bash
pip install numpy scikit-learn
```
Run the Python script:
python digit_classification_nn.py
