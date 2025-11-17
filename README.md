# 🤖 End-to-End Neural Network From Scratch Project

## 📘 Overview
This project demonstrates how to build a **fully functional feedforward neural network from scratch** using only **NumPy**, without any machine learning frameworks. It’s a beginner-friendly yet practical project to understand the mathematics and workflow behind neural networks.

## 🔄 Project Workflow

### 📁 Data Loading
* Worked with **synthetic 5×6 binary image data** representing characters **A, B, and C**.
* Each sample contains **30 pixel features** and a corresponding label.

### 🧹 Preprocessing
* Normalized pixel values to ensure stable training.
* Converted targets into one-hot encoded vectors for multi-class classification.

### 🧠 Model Building
* Implemented a **custom neural network** with:

  * Input layer (30 neurons)
  * Hidden layer with activation (ReLU/Sigmoid)
  * Output layer for 3 classes
* Coded forward propagation, backward propagation, loss computation, and weight updates manually.

### 🏋️ Training
* Trained the network using gradient descent.
* Observed decreasing loss and improving accuracy across epochs.

## 📈 Results

| Metric         | Value                                                     |
| -------------- | --------------------------------------------------------- |
| Model Type     | Custom Feedforward Neural Network                         |
| Accuracy       | Achieved strong classification accuracy on synthetic data |
| Example Output | Correctly classified test samples of A, B, and C          |

## 🧰 Requirements
```
pip install numpy
```

Run the notebook:
```
jupyter notebook Neural_networks.ipynb
```
