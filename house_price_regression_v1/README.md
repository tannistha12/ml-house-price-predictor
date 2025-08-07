# 🏡 House Price Regression - v1

This notebook implements a **Linear Regression model** to predict house prices using the famous [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## 📌 Project Overview

- **Objective:** Predict housing sale prices based on property features
- **Algorithm Used:** Linear Regression (Scikit-learn)
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

---

## 📊 Dataset

- **Source:** Kaggle
- **Files Used:**
  - `train.csv` — training data with labels
    
---

## 🧠 Features Used

| Feature | Description                  |
|--------|-------------------------------|
| OverallQual | Overall material and finish quality |
| GrLivArea   | Above ground living area (sq ft)    |
| GarageCars  | Size of garage in car capacity      |
| TotalBsmtSF | Total basement area (sq ft)         |
| GarageArea  | Size of the garage (sq ft)          |
| 1stFlrSF    | First floor area (sq ft)            |
| FullBath    | Number of full bathrooms            |
| YearBuilt   | Year the house was built            |

---

## 📈 Results

| Metric     | Score       |
|------------|-------------|
| MAE        | 24,932.67   |
| RMSE       | 39,558.88   |
| R² Score   | 0.7960      |

> Decent performance for a baseline model using minimal feature engineering.

---

## ✨ Key Learnings

- Understood how to:
  - Load and explore structured tabular data
  - Handle missing values and categorical encoding
  - Train/test split and apply Linear Regression
  - Evaluate regression performance using multiple metrics
  - Visualize model predictions and residuals

---

## 💡 Future Improvements

- Try **Ridge/Lasso/ElasticNet** regularization
- Engineer new features (like price per sq ft, year bins)
- Add pipeline and cross-validation
- Experiment with tree-based models (Random Forest, XGBoost)

---

## 📁 File Info

| File | Description |
|------|-------------|
| `house_price_regression_v1.ipynb` | Main notebook for this version |
| `README.md` | You’re here! Overview of this version |

---

## 🔗 Related Work

- [Original notebook (basic model)](../notebooks/house_price_model.ipynb)

---

## 🤝 Author

- 👤 **Tan**
- 🎓 B.Tech CSE | 3rd Year
- 🔍 Exploring Machine Learning, Open Source & Research
