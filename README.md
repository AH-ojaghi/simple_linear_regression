

# 🐣 Simple Linear Regression – Chicken and Egg Problem

This project implements a **simple linear regression** model to explore the classic "chicken and egg" problem using Python and NumPy. The goal is to predict the number of eggs based on the number of chickens using a basic linear model.

### 📊 Problem Statement

Given the dataset below:

| Chickens (X) | Eggs (Y) |
|--------------|----------|
| 1            | 2        |
| 2            | 6        |
| 3            | 8        |
| 4            | 11       |
| 6            | 15       |
| 9            | 21       |
| 10           | 30       |
| 15           | 40       |
| 13           | 34       |

We attempt to fit a linear regression line of the form:

```
h(x) = θ₀ + θ₁ * x
```

And answer questions like:
> **If x = 8, what is your prediction for y (number of eggs)?**

### 📌 Features

- Manual implementation of gradient descent
- Visualization of training data and prediction line using Matplotlib
- Easy-to-understand code structure and documentation

### 🧪 Technologies Used

- Python 🐍
- NumPy 🧮
- Matplotlib 📈
- Jupyter Notebook 📓

### 📷 Dataset Visualization

<p align="center">
  <img width="80%" src="https://drive.google.com/uc?id=1ErKMZJCEetBOX_zRVLFt2ohrfEFa5WqW">
</p>

### 🚀 Getting Started

#### Clone the repository

```bash
git clone https://github.com/AH-ojaghi/simple_linear_regression.git
cd simple-linear-regression
```

#### Install dependencies

Make sure you have Python and Jupyter installed:

```bash
pip install numpy matplotlib notebook
```

#### Run the notebook

```bash
jupyter notebook simple_linear_regression.ipynb
```

### 🤖 Output Example

The notebook guides you through plotting the data, calculating the cost function, and predicting values using the learned linear model.

---

### 💡 Author

Created by [Amirhossein Ojaghi](https://github.com/AH-ojaghi) 

