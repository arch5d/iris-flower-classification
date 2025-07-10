# Iris Flower Classification

This repository contains a complete machine learning project for classifying Iris flower species using scikit-learn. It includes data exploration, visualization, model training with hyperparameter tuning, and evaluation.

---

## Overview

- **Dataset**: Iris (150 samples, 3 classes: setosa, versicolor, virginica)
- **Features**:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- **Goal**: Predict the species based on measurements
- **Algorithm**: K-Nearest Neighbors (KNN) with GridSearchCV tuning

---

## Results

- **Best K (via GridSearchCV)**: 5
- **Test Accuracy**: ~93%

**Confusion Matrix:**

[[10 0 0]
[ 0 10 0]
[ 0 2 8]]

yaml
Copy
Edit

---

## Visual Outputs

Below are typical visual outputs generated in the notebook:

### 1. Pairplot for Exploratory Data Analysis
*(Shows clear separation among species)*

![image](https://github.com/user-attachments/assets/a50d0844-e26d-4388-b6b6-a4ff3344e937)


---

### 2. Confusion Matrix Heatmap
*(Highlights prediction performance across classes)*

![image](https://github.com/user-attachments/assets/b58262e6-fed1-41ac-92d3-f60bbaf26797)


---


## How to Run

### Option 1: Google Colab (Recommended)

- Open in Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EnPQCpEFTpuqrgF8b8jMMzY2bx3MVi-6#scrollTo=bQEIvMwbtLk9)

- No local setup needed.

---

### Option 2: Local Environment

Clone this repository:


git clone https://github.com/YOUR_USERNAME/iris-flower-classification.git
cd iris-flower-classification
pip install -r requirements.txt
Then open the notebook in Jupyter or VS Code.

Requirements
Python 3.7+

pandas

numpy

matplotlib

seaborn

scikit-learn

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
scikit-learn for providing the Iris dataset.

Seaborn and Matplotlib for visualization.

---

## Author

*Made by @arch5d*

---
