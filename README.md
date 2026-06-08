# Machine Learning From Scratch & Scikit-Learn

A collection of Machine Learning algorithms implemented both **from scratch using NumPy** and **using Scikit-Learn** to understand the mathematical foundations as well as industry-standard implementations.

## 🚀 Project Overview

This repository is designed to bridge the gap between theory and practical implementation of Machine Learning algorithms.

Each algorithm is implemented in two ways:

1. **From Scratch**
   - Built using Python and NumPy.
   - Focuses on understanding the underlying mathematics.
   - Includes manual implementation of cost functions, gradient descent, and optimization techniques.

2. **Scikit-Learn**
   - Uses the Scikit-Learn library.
   - Demonstrates real-world usage and best practices.
   - Provides performance comparison with custom implementations.

---

## 📚 Algorithms Covered (Im Progress)

### Regression

- Linear Regression
  - Univariate Linear Regression
  - Multivariate Linear Regression

- Polynomial Regression
- Regularized Linear Regression

### Classification

- Logistic Regression
- Multi-Class Classification
- Decision Trees
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)
- Naive Bayes

### Clustering

- K-Means Clustering
- Hierarchical Clustering

### Dimensionality Reduction

- Principal Component Analysis (PCA)

### Neural Networks

- Feed Forward Neural Networks
- Deep Learning Fundamentals

---

## 🧠 Concepts Implemented From Scratch

This repository focuses heavily on understanding the mathematics behind Machine Learning.

Implemented manually:

- Gradient Descent
- Batch Gradient Descent
- Cost Functions
- Sigmoid Function
- Feature Scaling
- Normalization
- Vectorization
- Forward Propagation
- Backpropagation
- Regularization
- Model Evaluation Metrics

---

## 📂 Repository Structure

```text
Machine-Learning/

├── datasets/
│   ├── housing.csv
│   ├── admissions.csv
│   └── ...
│
├── from_scratch/
│   ├── linear_regression/
│   ├── logistic_regression/
│   ├── kmeans/
│   └── ...
│
├── scikit_learn/
│   ├── linear_regression/
│   ├── logistic_regression/
│   ├── decision_tree/
│   └── ...
│
├── images/
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/PiyushAwasthi-2709/Machine-Learning-Labs.git
```

Move into the project directory:

```bash
cd machine-learning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📦 Dependencies

- Python 3.10+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

Install manually:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
```

---

## 📊 Learning Objectives

By working through this repository, you will learn:

- How Machine Learning algorithms work internally.
- The mathematics behind optimization.
- Cost function derivation and implementation.
- Gradient computation and parameter updates.
- Data preprocessing techniques.
- Model evaluation and performance analysis.
- How industry-standard libraries implement the same algorithms.

---

## 🔍 Example Workflow

### From Scratch

```python
model = LogisticRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

### Scikit-Learn

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

## 📈 Future Additions

- XGBoost
- LightGBM
- Neural Networks
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Transformers
- Reinforcement Learning

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to open an issue or submit a pull request.

---

## ⭐ Acknowledgements

This repository is inspired by:

- Andrew Ng's Machine Learning Specialization
- Hands-On Machine Learning
- Scikit-Learn Documentation
- Deep Learning Specialization

If you find this repository useful, consider giving it a ⭐ on GitHub.
