# Handwritten Digit Recognition Using Deep Learning

A deep learning project that classifies handwritten digits (0–9) using the MNIST dataset. This project implements and compares three neural network architectures—**Perceptron**, **Artificial Neural Network (ANN)**, and **Convolutional Neural Network (CNN)**—to evaluate their performance on handwritten digit classification.

> **Repository:**  
> https://github.com/Sanjayduduka45/Handwritten-Digit-Recognition-Using-Deep-Learning

---

## Project Overview

This project demonstrates the complete workflow of image classification using neural networks, from data preprocessing to model evaluation. Three different architectures are trained on the same dataset and compared using accuracy, loss curves, confusion matrices, and sample predictions.

The CNN model achieves the highest performance by effectively learning spatial features from handwritten digit images. CNNs are widely recognized as the standard approach for image classification tasks because of their ability to automatically extract hierarchical visual features. :contentReference[oaicite:0]{index=0}

---

## Repository Structure

```
Handwritten-Digit-Recognition-Using-Deep-Learning/
│
├── .venv/
│
├── mnist_train_8_12_11PM.csv      # Training dataset
├── mnist_test.csv                 # Testing dataset
│
├── number.ipynb                   # Complete project implementation
│
├── requirements.txt               # Required Python libraries
│
└── README.md
```

---

## Dataset

**Dataset:** MNIST Handwritten Digit Dataset

| Property | Value |
|----------|-------|
| Classes | 10 (Digits 0–9) |
| Image Size | 28 × 28 pixels |
| Features | 784 |
| Training Samples | 60,000 |
| Test Samples | 10,000 |
| Image Format | Grayscale |

---

## Project Workflow

- Load MNIST dataset
- Data inspection
- Missing value check
- Duplicate record check
- Train-Test split
- Data normalization
- One-Hot Encoding
- Model training
- Model evaluation
- Performance comparison
- Visualization of results

---

## Models Implemented

### Perceptron

- Input Layer
- Dense Output Layer
- Softmax Activation
- SGD Optimizer

---

### Artificial Neural Network (ANN)

Architecture

```
Input

↓

Dense (128)

↓

Dense (64)

↓

Output (10)
```

Optimizer

- Adam

Activation

- ReLU
- Softmax

---

### Convolutional Neural Network (CNN)

Architecture

```
Input (28×28×1)

↓

Conv2D (32)

↓

MaxPooling2D

↓

Conv2D (64)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128)

↓

Dropout

↓

Output (10)
```

Optimizer

- Adam

Activation

- ReLU
- Softmax

---

## Results

| Model | Test Accuracy |
|--------|--------------:|
| Perceptron | **91.06%** |
| ANN | **76.29%** |
| CNN | **98.99%** |

CNN achieved the best classification performance among the implemented models.

---

## Visualizations

The notebook includes

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Validation Accuracy Comparison
- Confusion Matrix
- Final Accuracy Comparison
- Sample Prediction Comparison

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## Installation

Clone the repository

```bash
git clone https://github.com/Sanjayduduka45/Handwritten-Digit-Recognition-Using-Deep-Learning.git
```

Move to the project folder

```bash
cd Handwritten-Digit-Recognition-Using-Deep-Learning
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
number.ipynb
```

Run all cells.

---

## Requirements

```
tensorflow
keras
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Key Learning Outcomes

- Image preprocessing
- Data normalization
- One-Hot Encoding
- Neural Networks
- Deep Learning
- CNN Architecture
- Model Evaluation
- Confusion Matrix Analysis
- Performance Comparison
- Image Classification

---

## Future Improvements

- Hyperparameter tuning
- Early Stopping
- Batch Normalization
- Data Augmentation
- Model Checkpointing
- Streamlit-based deployment
- Real-time handwritten digit prediction

---

## Author

**Sanjay Duduka**

**Machine Learning | Data Science | Python | Deep Learning**

**GitHub**

https://github.com/Sanjayduduka45

**Repository**

https://github.com/Sanjayduduka45/Handwritten-Digit-Recognition-Using-Deep-Learning

---

## License

This project is intended for educational and learning purposes.