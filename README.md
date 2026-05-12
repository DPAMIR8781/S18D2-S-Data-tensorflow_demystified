#  TensorFlow & Keras Fundamentals

This project explores the foundations of deep learning using TensorFlow and Keras.
The notebook demonstrates tensor operations, neural network architectures, CPU/GPU comparisons, regression models, classification models, and regularization techniques.

---

#  Project Overview

The main goal of this project is to understand:

- TensorFlow tensor mechanics
- Keras Sequential & Functional APIs
- Neural network architecture design
- Regression and classification workflows
- GPU vs CPU computation differences
- Overfitting reduction techniques

---

#  Topics Covered

##  Tensor Fundamentals

- Tensor creation
- Tensor shapes
- Tensor operations
- Tensor ↔ NumPy conversions
- Sparse tensors
- Ragged tensors

---

##  Neural Networks with Keras

### Sequential API
- Dense layers
- Activation functions
- Model summaries

### Functional API
- Input tensors
- Multi-layer architectures
- Flexible model creation

---

##  TensorFlow vs NumPy

Performance comparisons between:

- NumPy matrix multiplication
- TensorFlow CPU operations
- TensorFlow GPU operations

Matrix multiplication benchmarks were visualized using Matplotlib.

---

##  Forest Fires Dataset

The project uses the `forest_fires` dataset from `tensorflow_datasets`.

### Workflow:
- Load dataset
- Train/Test split
- Build regression models
- Train neural networks
- Evaluate convergence behavior

---

#  Model Architectures

## Regression Model

- Dense(50, relu)
- Dense(20, relu)
- Dense(1)

Loss Function:
- Mean Squared Error (MSE)

Optimizer:
- Adam

---

## Binary Classification Model

- Sigmoid output layer
- Binary Crossentropy loss

---

## Multi-Class Classification Model

- Softmax output layer
- Sparse Categorical Crossentropy loss

---

#  Regularization Techniques

To reduce overfitting:

-  Dropout
-  BatchNormalization
-  EarlyStopping

These techniques improved model stability and validation performance.

---

#  Model Training Visualization

Training and validation losses were visualized to analyze:

- convergence
- overfitting
- training stability

---

#  GPU / CPU Notes

TensorFlow successfully detected CPU execution.

No GPU device was available in the local environment.
For larger deep learning workloads, GPU acceleration can significantly improve training speed.

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

#  Repository Structure

```bash
.
├── recap.ipynb
├── README.md
└── assets/
```

---

# ▶️ Run the Project

Clone the repository:

```bash
git clone https://github.com/DPAMIR8781/S18D2-S-Data-tensorflow_demystified.git
```

Install dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn tensorflow-datasets
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📚 Learning Outcomes

By completing this project, the following concepts were practiced:

- Deep learning fundamentals
- Tensor manipulation
- Neural network construction
- Model regularization
- TensorFlow ecosystem usage
- GPU/CPU performance understanding
- Sequential & Functional Keras APIs

---

#  GitHub Repository

👉 https://github.com/DPAMIR8781/S18D2-S-Data-tensorflow_demystified
