<div align="center">

# 🔢 Handwritten Digit Recognition Using Deep Learning

### Perceptron • Artificial Neural Network (ANN) • Convolutional Neural Network (CNN)

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

</p>

<p align="center">

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</p>

---

### 📊 CNN achieved **98.99% Test Accuracy** on the MNIST Handwritten Digit Dataset.

</div>

---

# 📖 Overview

This project implements and compares three neural network architectures for handwritten digit recognition using the **MNIST** dataset.

The objective is to analyze how model complexity affects image classification performance by training:

- Perceptron
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

The project includes complete data preprocessing, model training, evaluation, visualization, and comparative analysis.

---

# ✨ Features

- 📥 Data Loading & Inspection
- 🧹 Data Preprocessing
- 🔄 Data Normalization
- 🏷️ One-Hot Encoding
- 🧠 Perceptron Implementation
- 🤖 ANN Implementation
- 🖼️ CNN Implementation
- 📈 Training & Validation Curves
- 📊 Confusion Matrix
- 🔍 Sample Predictions
- 📉 Model Performance Comparison

---

# 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Programming Language | ![Python](https://skillicons.dev/icons?i=python) Python |
| Deep Learning | ![TensorFlow](https://skillicons.dev/icons?i=tensorflow) TensorFlow & Keras |
| Machine Learning | Scikit-Learn |
| Data Analysis | ![Pandas](https://skillicons.dev/icons?i=pandas) Pandas • ![NumPy](https://skillicons.dev/icons?i=numpy) NumPy |
| Visualization | Matplotlib • Seaborn |
| IDE | ![VS Code](https://skillicons.dev/icons?i=vscode) VS Code |
| Notebook | ![Jupyter](https://skillicons.dev/icons?i=py) Jupyter Notebook |
| Version Control | ![Git](https://skillicons.dev/icons?i=git) Git |
| Repository | ![GitHub](https://skillicons.dev/icons?i=github) GitHub |

---

# 📂 Repository Structure

```
Handwritten-Digit-Recognition-Using-Deep-Learning
│
├── number.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

**MNIST Handwritten Digit Dataset**

| Property | Value |
|----------|-------|
| Classes | 10 |
| Image Size | 28 × 28 |
| Features | 784 |
| Training Samples | 60,000 |
| Testing Samples | 10,000 |

---

# ⚙️ Workflow

```text
Load Dataset
      │
      ▼
Data Inspection
      │
      ▼
Preprocessing
      │
      ▼
Normalization
      │
      ▼
One-Hot Encoding
      │
      ▼
Train Models
      │
      ▼
Evaluation
      │
      ▼
Performance Comparison
```

---

# 🧠 Models

## 1️⃣ Perceptron

- Dense Layer
- Softmax Activation
- SGD Optimizer

---

## 2️⃣ Artificial Neural Network (ANN)

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

---

## 3️⃣ Convolutional Neural Network (CNN)

```
Input (28×28×1)

↓

Conv2D (32)

↓

MaxPooling

↓

Conv2D (64)

↓

MaxPooling

↓

Flatten

↓

Dense (128)

↓

Dropout

↓

Softmax
```

---

# 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| 🟢 CNN | **98.99%** |
| 🔴 Perceptron | **91.06%** |
| 🟠 ANN | **76.29%** |

---

# 📊 Visualizations

The notebook includes

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Accuracy Comparison
- Confusion Matrix
- Sample Predictions

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Sanjayduduka45/Handwritten-Digit-Recognition-Using-Deep-Learning.git
```

Move into the project

```bash
cd Handwritten-Digit-Recognition-Using-Deep-Learning
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter

```bash
jupyter notebook
```

Open

```
number.ipynb
```

Run all cells.

---

# 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
jupyter
notebook
ipykernel
```

---

# 📚 Learning Outcomes

- Image Classification
- Deep Learning Fundamentals
- CNN Architecture
- Model Evaluation
- Data Preprocessing
- One-Hot Encoding
- Performance Analysis
- Confusion Matrix Interpretation

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- Batch Normalization
- Early Stopping
- Data Augmentation
- Streamlit Deployment
- Real-Time Digit Recognition

---

# 👨‍💻 Author

## Sanjay Duduka

Machine Learning • Data Science • Python • Deep Learning

<p>

<a href="https://github.com/Sanjayduduka45">
<img src="https://skillicons.dev/icons?i=github" width="40"/>
</a>

<a href="https://www.linkedin.com/in/sanjayduduka">
<img src="https://skillicons.dev/icons?i=linkedin" width="40"/>
</a>

</p>

GitHub Repository:

**https://github.com/Sanjayduduka45/Handwritten-Digit-Recognition-Using-Deep-Learning**

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>