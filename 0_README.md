# 📊 Linear Regression from Scratch: TV Advertising vs Sales

This project demonstrates how to implement **Simple Linear Regression** manually using Python and NumPy, without relying on machine learning libraries like `scikit-learn`.

We explore the relationship between **TV advertising budgets** and **product sales** using the classic `Advertising.csv` dataset.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `linear_regression_tv_sales.ipynb` | Main Colab notebook containing code, explanations, plots |
| `README.md` | Project description and usage instructions |
| `linear regression scatter plot.png` | Exported regression line plot |


---

## 🧠 What I Learned

- How to calculate slope and intercept using the **Least Squares method**
- How to visualize data and regression line with `matplotlib`
- How to evaluate model accuracy using **R-squared**
- The mathematical intuition behind **linear regression**

---

## 🔬 Dataset Overview

Dataset: [Advertising.csv](https://www.statlearning.com/s/Advertising.csv)  
From the book *An Introduction to Statistical Learning*

| Column | Description |
|--------|-------------|
| `TV` | TV advertising budget (in thousands) |
| `sales` | Product sales (in thousands of units) |

We focus only on the relationship between `TV` and `sales`.

---

## 📈 Regression Equation

The best-fit line is computed as:

```math
Sales = m × TV + c
