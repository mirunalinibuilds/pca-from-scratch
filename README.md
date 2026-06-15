# PCA From Scratch

> Understanding Principal Component Analysis by building it from first principles using NumPy.

## 🚀 The Hook

Most PCA tutorials hide the mathematics behind a single line of code.

```python
PCA(n_components=2)
```

This project takes a different approach.

Instead of relying on scikit-learn, PCA is implemented step-by-step using NumPy to demonstrate exactly how dimensionality reduction works under the hood.

Using the Breast Cancer Wisconsin Dataset, we reduce a 30-dimensional dataset into 2 principal components while preserving as much information as possible.

---

## ✨ What You'll Learn

By exploring this notebook, you'll understand:

✅ Data Standardization

✅ Covariance Matrices

✅ Eigenvalues & Eigenvectors

✅ Explained Variance

✅ Principal Components

✅ Dimensionality Reduction

✅ PCA Visualization

---

## 📊 Dataset

**Breast Cancer Wisconsin Dataset**

* 569 samples
* 30 numerical features
* Binary classification problem
* Included directly in scikit-learn

Goal:

Reduce 30 dimensions into 2 dimensions while retaining the most important information.

---

## 🧠 PCA Workflow

```text
Raw Data
    ↓
Standardization
    ↓
Covariance Matrix
    ↓
Eigenvalue Decomposition
    ↓
Sort Components
    ↓
Select Top Principal Components
    ↓
Project Data
    ↓
2D Visualization
```

---

## ⚙️ Features

### 🔹 Manual PCA Implementation

No PCA libraries used.

Everything is built from scratch using NumPy.

### 🔹 Mathematical Understanding

Learn the concepts behind:

* Covariance
* Variance
* Eigenvalues
* Eigenvectors

### 🔹 Dimensionality Reduction

Transform a high-dimensional dataset into a lower-dimensional representation.

### 🔹 Data Visualization

Visualize complex data in 2 dimensions using the principal components.

---

## 🛠️ Tech Stack

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Core Programming          |
| NumPy            | Mathematical Computations |
| Pandas           | Data Handling             |
| Matplotlib       | Visualization             |
| Jupyter Notebook | Development Environment   |

---

## 📂 Project Structure

```text
pca-from-scratch/
│
├── pca_from_scratch.ipynb
└── README.md
```

---

## ⚡ Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/mirunalinibuilds/pca-from-scratch.git
```

### 2. Navigate into the Project

```bash
cd pca-from-scratch
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
```

### 4. Open the Notebook

```bash
jupyter notebook
```

Run the notebook cells step-by-step and explore how PCA is implemented from scratch.

---

## 📈 Results

The notebook demonstrates:

* Feature standardization
* Covariance matrix construction
* Eigenvalue decomposition
* Principal component selection
* Dimensionality reduction from 30 features to 2
* Visualization of transformed data

Plots and visual outputs are included directly inside the notebook.

---

## 🎯 Why This Project Matters

Many machine learning practitioners use PCA without understanding what happens internally.

This project focuses on building intuition first.

By implementing PCA manually, you gain a deeper understanding of one of the most important dimensionality reduction techniques in machine learning.

---

## 🔮 Future Improvements

* Compare manual PCA with scikit-learn PCA
* Add cumulative explained variance plots
* Add scree plot visualization
* Extend to larger real-world datasets
* Benchmark performance against library implementations

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you find a bug or have ideas for enhancement:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

---

## ⭐ Support

If this project helped you understand PCA, consider giving the repository a star.

It helps more learners discover the project and supports future educational content.

---

Built with curiosity, NumPy, and a desire to understand machine learning beyond the black box.
