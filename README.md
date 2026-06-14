Week 1 Assignment — ML Foundations

This repository contains my Week 1 assignment notebook .

Topics Covered

Part 1 — Python Fundamentals
Data types
Control flow
Dictionaries, sets, list comprehensions
Exception handling
Functions & lambda expressions

Part 2 — NumPy
Array creation
Reshaping arrays
Indexing & slicing
Matrix operations
Dot products

Part 3 — Pandas
Series vs DataFrames
iloc and loc
Filtering data
GroupBy operations
Handling missing values

Part 4 — Linear Algebra
Vectors and matrices
Matrix multiplication
Eigenvalues & eigenvectors
Singular Value Decomposition (SVD)

Part 5 — Statistics
Descriptive statistics
Hypothesis testing
Error metrics
Distribution testing
Population Stability Index (PSI)

Part 6 — Probability Theory
Probability basics
Common distributions
Bayes theorem
Central Limit Theorem (CLT)

 Notebook
- `week1_Nishita_Gupta_Jecrc_Foundation.ipynb`

 Tools & Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Statsmodels

Author
Nishita Gupta







WEEK 4
# CIFAR-10 Image Classification using ANN and CNN

## 📌 Project Overview

This project demonstrates image classification on the **CIFAR-10** dataset using Deep Learning techniques in TensorFlow/Keras. It compares the performance of a traditional **Artificial Neural Network (ANN)** with a **Convolutional Neural Network (CNN)** and an **Advanced CNN** enhanced with data augmentation and regularization techniques.

The project helps understand why CNNs outperform ANNs for image classification tasks by preserving spatial information and learning hierarchical image features.

---

## 🎯 Objectives

* Load and preprocess the CIFAR-10 dataset.
* Build a baseline Artificial Neural Network (ANN).
* Build a Convolutional Neural Network (CNN).
* Compare ANN and CNN performance.
* Apply data augmentation techniques.
* Improve CNN performance using Batch Normalization, Dropout, and Early Stopping.
* Visualize validation accuracy and compare model performance.

---

## 📂 Dataset

The project uses the **CIFAR-10** dataset containing **60,000 RGB images** of size **32 × 32 pixels**.

* Training Images: **50,000**
* Test Images: **10,000**
* Number of Classes: **10**

Classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

---

## 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pandas
* Google Colab / Jupyter Notebook

---

## 🚀 Project Workflow

1. Load the CIFAR-10 dataset.
2. Normalize image pixel values from **0–255** to **0–1**.
3. Build a baseline ANN using Dense and Dropout layers.
4. Build a CNN using:

   * Conv2D
   * BatchNormalization
   * MaxPooling2D
   * Flatten
   * Dense layers
5. Train both models using the Adam optimizer and Sparse Categorical Crossentropy loss.
6. Compare validation accuracy curves.
7. Apply Data Augmentation:

   * RandomFlip
   * RandomRotation
   * RandomZoom
8. Build an advanced CNN with:

   * Increased Dense layers
   * Filters (32 → 64 → 128)
   * EarlyStopping callback
   * 20 training epochs

---

## 📊 Results

The notebook compares:

* ANN Validation Accuracy
* CNN Validation Accuracy
* Advanced CNN Validation Accuracy

A final comparison table displays test accuracy for all models.

Typical performance:

| Model        | Approximate Accuracy |
| ------------ | -------------------- |
| ANN          | 50–55%               |
| CNN          | 70–75%               |
| Advanced CNN | 80–85%               |

---

## 📈 Visualizations

The project includes:

* Sample CIFAR-10 images
* ANN vs CNN validation accuracy curves
* Final model comparison
* Test accuracy comparison table

---

## 📚 Learning Outcomes

Through this project, students learn:

* Image preprocessing
* Neural Networks vs Convolutional Neural Networks
* Feature extraction using convolutions
* Batch Normalization
* Dropout regularization
* Data Augmentation
* Early Stopping
* Model evaluation and comparison

---

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install TensorFlow if required.
3. Run all cells sequentially.
4. Observe training progress and evaluation metrics.
5. Compare ANN, CNN, and Advanced CNN performance.

---

## 👩‍💻 Author

**Nishita Gupta**

Deep Learning Learning Project using TensorFlow and Keras on the CIFAR-10 Image Classification dataset.
