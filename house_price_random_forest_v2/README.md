# House Price Prediction — Random Forest Regression (v2)

This notebook implements a **Random Forest Regression model** to predict house prices using the famous [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## 📌 Project Overview

- **Objective:** Predict housing sale prices based on property features
- **Algorithm Used:** Random Forest Regression (Ensemble Tree-Based Model)
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
| MAE        | 18,452.13   |
| RMSE       | 29,784.41   |
| R² Score   | 0.8752      |

✅ Random Forest significantly outperformed Linear Regression by:

- Handling non-linear relationships
- Capturing feature interactions automatically
- Reducing variance via ensemble averaging

---

## ✨ Key Learnings

- Understood how to:
  - How to preprocess categorical + numerical features together
  - Applying Random Forest Regression for tabular datasets
  - Evaluating models using multiple regression metrics (MAE, RMSE, R²)
  - Importance of model comparison: baseline vs advanced

---

## 💡 Future Improvements

- Tune hyperparameters (n_estimators, max_depth, min_samples_split)
- Add feature importance visualization
- Try Gradient Boosting (XGBoost, LightGBM, CatBoost)
- Use cross-validation for more robust results

---

## 📁 File Info

| File | Description |
|------|-------------|
| `house_price_random_forst_v2.ipynb` | Main notebook for this version |
| `README.md` | You’re here! Overview of this version |

---

## 🔗 Related Work

- [Original notebook (basic model)](../notebooks/house_price_model.ipynb)

---

## 🤝 Author

- 👤 **Tan**
- 🎓 B.Tech CSE | 3rd Year
- 🔍 Exploring Machine Learning, Open Source & Research
