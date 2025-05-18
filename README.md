# 🔌 BCG Power Co. – Electricity Consumption Modeling

## 📈 Objective
The aim of this project is to analyze and model electricity consumption data for BCG Power Co. by applying feature engineering and machine learning techniques to predict future usage patterns and optimize operations.

## 📂 Project Structure

- `Task 3 - Feature Engineering.ipynb`: Preprocessing and feature extraction
- `Task 4 - Modeling.ipynb`: Model training, evaluation, and prediction
- `main.py`: Combined Python script for feature engineering and modeling
- `README.md`: Project documentation (this file)

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Matplotlib / Seaborn (for visualization)
- Machine Learning models: Linear Regression, Decision Tree Regressor

## 🧪 Process Overview

### 1. Feature Engineering
- Convert date columns to datetime format
- Extract temporal features: year, month, day, hour
- Calculate usage deltas
- Drop null or irrelevant columns

### 2. Modeling
- Train/Test split
- Train models: Linear Regression, Decision Tree
- Evaluate using RMSE and R²
- Output predictions for review

## 📊 Model Evaluation Metrics

- **Root Mean Squared Error (RMSE)**
- **R² Score**

## 🚀 How to Run

### Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
