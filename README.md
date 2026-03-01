# 🧠 Multi-Layer Perceptron — Deep Learning (ANN Applications)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=flat-square&logo=keras)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

> A hands-on deep learning practice project implementing **Artificial Neural Networks (ANN)** using the **Multi-Layer Perceptron (MLP)** architecture across three real-world datasets.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Results](#-results)
- [Key Concepts Covered](#-key-concepts-covered)
- [Author](#-author)

---

## 🔍 Overview

This repository explores the fundamentals and applications of **Multi-Layer Perceptrons (MLPs)** — a class of feedforward artificial neural networks. Each notebook tackles a different problem type (binary classification, regression, and multi-class classification) to provide broad exposure to ANN-based deep learning workflows.

---

## 📂 Projects

### 1. 🏦 Customer Churn Prediction
**Notebook:** `Churn Prediction DL.ipynb`  
**Dataset:** `Churn_Modelling.csv`

Predicts whether a bank customer will churn (leave the bank) based on demographic and account features. This is a **binary classification** problem.

| Feature | Detail |
|---|---|
| Task | Binary Classification |
| Target | Exited (0 or 1) |
| Key Features | Credit Score, Geography, Age, Balance, Products |

---

### 2. 🎓 Graduate Admission Prediction
**Notebook:** `Graduate Admission Prediction DL.ipynb`  
**Dataset:** `Admission_Predict_Ver1.1.csv`

Predicts the probability of a student's admission to a graduate program based on academic scores and research experience. This is a **regression** problem.

| Feature | Detail |
|---|---|
| Task | Regression |
| Target | Chance of Admit (0.0 – 1.0) |
| Key Features | GRE Score, TOEFL Score, CGPA, SOP, LOR, Research |

---

### 3. ✍️ MNIST Handwritten Digit Classification
**Notebook:** `mnist-classification DL .ipynb`

Classifies handwritten digits (0–9) from the iconic MNIST dataset. This is a **multi-class classification** problem using fully connected MLP layers.

| Feature | Detail |
|---|---|
| Task | Multi-Class Classification (10 classes) |
| Target | Digit Label (0–9) |
| Input | 28×28 grayscale images (flattened) |

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Deep Learning:** TensorFlow / Keras
- **Data Manipulation:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure

```
Multi-Layer-Perceptron-Deep-Learning/
│
├── 📓 Churn Prediction DL.ipynb             # Binary classification — customer churn
├── 📓 Graduate Admission Prediction DL.ipynb # Regression — admission probability
├── 📓 mnist-classification DL .ipynb         # Multi-class — digit recognition
│
├── 📊 Churn_Modelling.csv                   # Dataset for churn prediction
├── 📊 Admission_Predict_Ver1.1.csv          # Dataset for admission prediction
│
└── 📄 README.md
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Clone the Repository

```bash
git clone https://github.com/sanzidd/Multi-Layer-Perceptron-Deep-Learning.git
cd Multi-Layer-Perceptron-Deep-Learning
```

### Run the Notebooks

```bash
jupyter notebook
```

Then open any `.ipynb` file from the Jupyter interface in your browser.

---

## 📊 Results

| Project | Task | Model Type | Metric |
|---|---|---|---|
| Customer Churn | Binary Classification | ANN (MLP) | Accuracy |
| Graduate Admission | Regression | ANN (MLP) | RMSE / R² Score |
| MNIST Classification | Multi-Class Classification | ANN (MLP) | Accuracy |

> Detailed results, loss/accuracy curves, and evaluation metrics are available inside each notebook.

---

## 🧩 Key Concepts Covered

- Building MLP architectures with Keras Sequential API
- Activation functions: ReLU, Sigmoid, Softmax
- Loss functions: Binary Crossentropy, MSE, Categorical Crossentropy
- Optimizers: Adam
- Regularization: Dropout, Batch Normalization
- Feature scaling and preprocessing with Scikit-learn
- Model evaluation and performance visualization

---

## 👤 Author

**Sanzid**  
[![GitHub](https://img.shields.io/badge/GitHub-sanzidd-181717?style=flat-square&logo=github)](https://github.com/sanzidd)

---

> ⭐ If you found this project helpful, feel free to star the repository and fork it for your own practice!
