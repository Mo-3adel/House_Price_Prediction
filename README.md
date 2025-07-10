# 🏠 House Prices Prediction with XGBoost and Preprocessing Pipelines

This project is a complete end-to-end machine learning workflow for predicting house prices using the famous [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The notebook includes EDA, feature preprocessing, model training, hyperparameter tuning, and performance evaluation using **XGBoost** integrated with **Scikit-learn Pipelines**.

---

## 📌 Project Highlights

- 📊 Exploratory Data Analysis (EDA)
- 🔧 Feature engineering and missing value treatment
- 🏗️ Column-wise preprocessing using `ColumnTransformer`
- 🔁 Pipelines for clean and reproducible ML workflow
- 🚀 Model training using `XGBoostRegressor`
- 📈 Evaluation with R², MAE, and RMSE
- 🔍 Hyperparameter tuning with `GridSearchCV` (optional)
- 📤 Ready for submission or production deployment

---

## 💼 Dataset

- Dataset: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Target: `SalePrice` (continuous)
- Features: 79 explanatory variables including numeric, ordinal, and categorical

---

## 🧪 Models Used

- ✅ Linear Regression (baseline)
- ✅ XGBoost Regressor (main model)
- ✅ Optionally: LightGBM, Random Forest, CatBoost (you can plug in via pipeline)

---

## 🧱 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn (for visualizations)
- Jupyter Notebook

---

## 📈 Evaluation Metrics

| Metric | Description | Example Value |
|--------|-------------|----------------|
| **R² Score** | Proportion of variance explained | `0.89` |
| **MAE** | Mean Absolute Error | `~14,700` |
| **RMSE** | Root Mean Squared Error | `~25,900` |

---

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Mo-3adel/House_Price_Prediction.git
   cd house-price-xgboost
   ```

2. Dowload the Dataset and change the train and test path:


3. Launch the notebook:
   ```bash
   jupyter notebook house-prices-prediction-with-xgboost-preproce-3.ipynb
   ```

---

## 📎 File Structure

```
├── house-prices-prediction-with-xgboost-preproce.ipynb
├── README.md

```

---

## 📌 TODO / Improvements

- [ ] Add LightGBM and CatBoost comparison
- [ ] Add feature importance plots
- [ ] Export trained model using `joblib`
- [ ] Deploy via Flask or Streamlit

---

## 📚 References

- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [Scikit-learn Pipelines](https://scikit-learn.org/stable/modules/compose.html)
- [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

---

## 📬 Contact

If you have any feedback or suggestions, feel free to reach out!

> ⭐ Star this repo if you found it helpful!
