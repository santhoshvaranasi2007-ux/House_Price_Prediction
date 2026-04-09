# House_Price_Prediction
# 🏠 House Price Prediction

A machine learning project that predicts median house prices using the Boston Housing dataset. The project compares **Ridge Regression** and **XGBoost** models with full exploratory data analysis and visualizations.

---

## 📌 Project Overview

This notebook-based project loads a housing dataset, performs EDA, trains two regression models, and evaluates their performance using standard metrics and cross-validation.

---

## 📂 Project Structure

```
House_Price_Prediction/
├── housing_price.ipynb       # Main Jupyter Notebook
├── housing.csv               # Dataset (Boston Housing)
├── graph1_data_overview.png  # EDA: Price distribution & Rooms vs Price
├── graph2_model_results.png  # Model: CV scores & Actual vs Predicted
├── graph3_distribution.png   # House Price Distribution histogram
└── README.md
```

---

## 🧠 Models Used

| Model | Description |
|-------|-------------|
| Ridge Regression | Linear model with L2 regularization (alpha=1.0) |
| XGBoost Regressor | Gradient boosting with 200 estimators, tuned hyperparameters |

---

## 📊 Dataset

**Source:** Boston Housing Dataset (`housing.csv`)
**Shape:** 506 rows × 14 columns
**Target Variable:** `medv` — Median value of owner-occupied homes in $1,000s

| Feature | Description |
|---------|-------------|
| `crim` | Per capita crime rate |
| `zn` | Proportion of residential land zoned for large lots |
| `indus` | Proportion of non-retail business acres |
| `chas` | Charles River dummy variable |
| `nox` | Nitric oxide concentration |
| `rm` | Average number of rooms per dwelling |
| `age` | Proportion of owner-occupied units built before 1940 |
| `dis` | Weighted distances to employment centres |
| `rad` | Accessibility to radial highways index |
| `tax` | Property tax rate per $10,000 |
| `ptratio` | Pupil-teacher ratio |
| `b` | Proportion of residents by town |
| `lstat` | % lower status of the population |
| `medv` | **Target** — Median house value ($1k) |

---

## ⚙️ Tech Stack

- **Python 3.13**
- `pandas`, `numpy` — Data manipulation
- `matplotlib`, `seaborn` — Visualization
- `scikit-learn` — Ridge Regression, train/test split, cross-validation, metrics
- `xgboost` — XGBoost Regressor

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/santhoshvaranasi2007-ux/House_Price_Prediction.git
cd House_Price_Prediction
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

3. Launch the notebook:
```bash
jupyter notebook housing_price.ipynb
```

4. Run all cells — results, metrics, and graphs will be generated automatically.

---

## 📈 Evaluation Metrics

- R² Score (Train & Test)
- RMSE (Root Mean Squared Error)
- 5-Fold Cross-Validation R²

---

## 📉 Visualizations

- `graph1_data_overview.png` — Price distribution + Rooms vs Price scatter
- `graph2_model_results.png` — CV scores bar chart + Actual vs Predicted scatter
- `graph3_distribution.png` — Full house price distribution histogram

---

## 👤 Author

**Santhosh Varanasi**
GitHub: [@santhoshvaranasi2007-ux](https://github.com/santhoshvaranasi2007-ux)

---

## 📄 License

This project is open-source and available under the MIT License.
