# Boston Housing Price Prediction using XGBoost

This project predicts house prices in Boston using the XGBoost regression model. The dataset is taken from the [CMU StatLib Boston Housing dataset](https://lib.stat.cmu.edu/datasets/boston).

---

## 📝 Dataset

- **Features (13):**
  - `CRIM` — per capita crime rate by town
  - `ZN` — proportion of residential land zoned for lots over 25,000 sq.ft.
  - `INDUS` — proportion of non-retail business acres per town
  - `CHAS` — Charles River dummy variable (1 if tract bounds river; 0 otherwise)
  - `NOX` — nitric oxides concentration (parts per 10 million)
  - `RM` — average number of rooms per dwelling
  - `AGE` — proportion of owner-occupied units built prior to 1940
  - `DIS` — weighted distances to five Boston employment centers
  - `RAD` — index of accessibility to radial highways
  - `TAX` — full-value property-tax rate per $10,000
  - `PTRATIO` — pupil-teacher ratio by town
  - `B` — 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
  - `LSTAT` — % lower status of the population
- **Target:**
  - `price` — Median value of owner-occupied homes in $1000s

---

## 📊 Project Workflow

1. Load and preprocess the dataset.
2. Explore data: summary statistics, missing values, and correlation heatmap.
3. Split data into training and test sets.
4. Train an XGBoost regressor.
5. Evaluate model performance using:
   - R² score
   - Mean Absolute Error (MAE)
6. Visualize actual vs predicted prices.

---

## ⚡ Dependencies

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
