# 🏡 House Price Prediction using Machine Learning

An end-to-end machine learning project that predicts residential house prices using the Ames Housing dataset. The project walks through data exploration, preprocessing, feature engineering, model training, evaluation, and interpretation.

---

## 📌 Project Overview

This project demonstrates a complete machine learning workflow:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Imputation
- One-Hot Encoding for categorical features
- Linear Regression
- Random Forest Regression
- Feature Importance Analysis
- Model Evaluation

---

## 📊 Dataset

- **Dataset:** Ames Housing Dataset
- **Rows:** 1,460
- **Columns:** 81
- **Target Variable:** `SalePrice`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis

Performed:

- Distribution analysis of house prices
- Missing value analysis
- Correlation analysis
- Feature importance analysis
- Summary statistics

---

## 🤖 Models Trained

### 1. Linear Regression (Top 5 Features)

Features:
- OverallQual
- GrLivArea
- GarageCars
- GarageArea
- TotalBsmtSF

**Performance**

| Metric | Value |
|--------|-------|
| R² Score | **0.792** |
| MAE | **$25,285** |

---

### 2. Linear Regression (All Numerical Features)

| Metric | Value |
|--------|-------|
| R² Score | **0.823** |
| MAE | **$23,000** |

---

### 3. Linear Regression (All Features)

Included:

- Numerical Features
- Categorical Features
- Missing Value Imputation
- One-Hot Encoding

| Metric | Value |
|--------|-------|
| R² Score | **0.875** |
| MAE | **$20,443** |

---

### 4. Random Forest Regression ⭐

Best performing model.

| Metric | Value |
|--------|-------|
| **R² Score** | **0.894** |
| **MAE** | **$17,494** |

---

## 📈 Feature Importance

Top predictors learned by the Random Forest model:

| Rank | Feature |
|-----:|---------|
| 1 | OverallQual |
| 2 | GrLivArea |
| 3 | TotalBsmtSF |
| 4 | 2ndFlrSF |
| 5 | 1stFlrSF |
| 6 | BsmtFinSF1 |
| 7 | LotArea |
| 8 | GarageArea |
| 9 | GarageCars |
| 10 | YearBuilt |

---

## 📷 Visualizations

The notebook includes:

- House Price Distribution
- Correlation Analysis
- Feature Importance Plot
- Actual vs Predicted Prices

---

## 💡 Key Findings

- House quality (`OverallQual`) is the strongest predictor of sale price.
- Larger living area generally leads to higher home values.
- Basement size and garage capacity significantly improve prediction accuracy.
- Incorporating categorical variables with One-Hot Encoding substantially improves model performance.
- Random Forest outperformed all Linear Regression models.

---

## 📁 Project Structure

```
house-price-prediction/
│
├── notebooks/
│   └── analysis.ipynb
│
├── images/
│   ├── house_price_distribution.png
│   ├── feature_importance.png
│   └── actual_vs_predicted.png
│
├── house_price_model.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

- XGBoost
- LightGBM
- Hyperparameter tuning
- Cross-validation
- Model deployment with Streamlit
- Feature selection optimization

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Regression Modeling
- Pipeline Construction
- Model Evaluation
- Data Visualization
