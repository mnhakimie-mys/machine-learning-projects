# 🚗 Car Price Prediction using Machine Learning

This project uses supervised machine learning to predict the price of a car based on various attributes such as engine size, horsepower, fuel type, and brand. It demonstrates a complete data science workflow: data cleaning, feature engineering, model training, evaluation, and visualization.

---

## 📊 Dataset

- Source: [CarPrice_Assignment.csv](https://www.kaggle.com/datasets/shaistashaikh/carprice-assignment) (*From Kanggle and uploaded to Google Drive*)
- Features include car specifications such as:
  - `CarName`
  - `fueltype`, `aspiration`
  - `enginesize`, `horsepower`
  - `carbody`, `brand`, etc.
- Target: `price`

---

## 🧠 Model Used

- **Random Forest Regressor** (from scikit-learn)
- Achieved strong performance with good RMSE and R² score on test data.

---

## 📈 Workflow Overview

1. **Data Loading & Exploration**
2. **Data Preprocessing**
   - Removed irrelevant columns (`car_ID`)
   - Extracted brand from `CarName`
   - One-hot encoded categorical features
3. **Train/Test Split**
4. **Model Training**
   - Used `RandomForestRegressor` from `scikit-learn`
5. **Evaluation**
   - RMSE and R² score
   - Actual vs Predicted price scatter plot

---

## 🔍 Sample Results

| Metric | Score |
|--------|-------|
| RMSE   | *1827* |
| R²     | *0.96* |

> The model shows strong predictive power and generalization on unseen car data.

---

## 📦 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib (for model saving)
- Google Colab (for development)

---
