# 🌽 Mycotoxin Prediction using Hyperspectral Imaging

This project focuses on predicting the concentration of **vomitoxin (DON)** in corn samples using **hyperspectral imaging data**. Using machine learning, we aim to forecast DON levels based on spectral reflectance across various wavelengths, providing a fast and scalable method for detecting contamination in agricultural products.

---

## 📂 Project Overview

- 🎯 **Goal**: Predict DON levels in corn samples using spectral data
- 📊 **Target Variable**: `vomitoxin_ppb` (parts per billion)
- 🌈 **Features**: 448 spectral reflectance values (wavelengths)
- 🧪 **Approach**: Machine learning with hyperparameter tuning

---

## 🧬 Dataset

- 🔢 **448 spectral features** representing wavelengths
- 🧹 **Missing values** handled using **median imputation**
- 📁 File name: `MLE-Assignment.csv`

---

## 📈 Results

After training and tuning the model, the following metrics were achieved:

- 🔹 **Mean Absolute Error (MAE)**: 3847.11 ppb  
- 🔹 **Root Mean Squared Error (RMSE)**: 11,410.97 ppb  
- 🔹 **R² Score**: 0.534  

> 🧠 These results indicate **moderate prediction accuracy**, with potential for improvement through advanced techniques.

---

## 📁 Project Structure

| File                     | Description                                     |
|--------------------------|-------------------------------------------------|
| `Mycotoxin_Prediction.ipynb` | Full notebook from data loading to model evaluation |
| `Report.pdf`             | Summary of methodology, results, and conclusions |

---

## 🚀 Future Improvements

- 🔁 Try ensemble models like **XGBoost** or **LightGBM**
- 🧪 Apply domain-specific **feature engineering**
- 🧠 Use **Optuna** for more advanced hyperparameter tuning
- 🌐 Deploy the model via **Flask** or **FastAPI**

---

## 🧰 Libraries & Tools

- [Scikit-Learn](https://scikit-learn.org/)
- [Optuna](https://optuna.org/) – Hyperparameter Optimization
- [SHAP](https://github.com/slundberg/shap) – Model Interpretability
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) – Visualization



