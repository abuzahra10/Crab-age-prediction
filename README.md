# 🦀 Crab Age Prediction using Huber Regressor

---

## 📌 Project Overview

This project addresses the challenge of predicting the **age of crabs** using a set of physical and biological measurements. The regression task leverages **Huber Regressor**, which provides robustness against outliers—an important aspect in real-world biological data. We enhance this model through feature scaling and polynomial expansion to better capture non-linear relationships.

---

## ✅ Objectives

- Preprocess and explore the crab dataset.
- Engineer features for optimal model performance.
- Apply a robust regression model that minimizes **Mean Absolute Error (MAE)**.
- Evaluate the model using standard regression metrics.

---

## 🧠 Approach

### 🔹 Data Preprocessing

- One-hot encoding applied to the categorical feature `Sex`.
- Columns reordered for better interpretability and feature grouping.
- **Visualizations included**:
  - Histograms & KDE plots (feature distribution)
  - Box plots (outlier detection)
  - Scatter plots (feature vs. target)
  - Correlation heatmap (relationship insights)

### 🔹 Feature Engineering

- Standardized numeric features using `StandardScaler`.
- Applied **polynomial feature transformation (degree = 3)** to uncover non-linear patterns.

### 🔹 Modeling

- Model used: **Huber Regressor**
  - Robust to outliers.
  - Regularization handled internally with the `alpha` parameter.
- Evaluation metrics:
  - Mean Squared Error (MSE)
  - R² Score
  - Mean Absolute Error (MAE)

---

## 📊 Evaluation Results

| Metric            | Value             |
|-------------------|-------------------|
| **MSE**           | `<your_value_here>` |
| **R² Score**      | `<your_value_here>` |
| **MAE**           | `<your_value_here>` |

> 💡 Replace `<your_value_here>` with your actual model results.

---

## 🔧 Tech Stack

- **Python**
- **Pandas, NumPy** – data handling
- **Matplotlib, Seaborn** – visualization
- **Scikit-learn** – modeling and preprocessing

---

## 🚀 How to Run

### 🔁 Clone the repository

```bash
git clone https://github.com/your-username/crab-age-prediction.git
cd crab-age-prediction
