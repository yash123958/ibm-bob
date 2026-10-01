# 📋 Project Plan — Car Price Prediction

## 🎯 Objective
Build a machine learning model that predicts the price of a car based on its specifications, and present the results in an interactive web dashboard.

---

## ✅ Phase 1 — Data Understanding

- [x] Load and explore `CarPrice.csv`
- [x] Check dataset shape (205 rows × 26 columns)
- [x] Identify target variable: `price`
- [x] Check for missing values → None found
- [x] Understand feature types (numeric vs categorical)

---

## ✅ Phase 2 — Data Preprocessing

- [x] Extract brand name from `CarName` column
- [x] Drop non-predictive columns (`car_ID`, `CarName`)
- [x] Label encode all categorical columns
- [x] Train / Test split → 80% train, 20% test
- [x] Standardise features using `StandardScaler`

---

## ✅ Phase 3 — Model Building

- [x] Choose algorithm: **Linear Regression**
- [x] Train model on training set
- [x] Predict on test set
- [x] Evaluate using R², RMSE, MAE

### Model Results

| Metric | Value |
|---|---|
| R² Score | 0.8411 |
| RMSE | $3,541.96 |
| MAE | $2,127.47 |

---

## ✅ Phase 4 — Dashboard

- [x] Build dark-themed HTML report (`report.html`)
- [x] Add KPI cards (dataset size, R², RMSE)
- [x] Add model info section
- [x] Build live price predictor form (24 inputs)
- [x] Embed Linear Regression in JavaScript (coefficients + scaler)
- [x] Add EDA charts (price distribution, brand, horsepower vs price)
- [x] Add Actual vs Predicted scatter chart

---

## ✅ Phase 5 — Cleanup & Submission

- [x] Remove unused files (Random Forest model, plots, scripts)
- [x] Keep only essential files: `CarPrice.csv`, `lr_model.json`, `report.html`
- [x] Write `README.md`
- [x] Write `PLAN.md`
- [ ] Deploy to Netlify / GitHub Pages
- [ ] Share link for submission

---

## 📁 Final File Structure

```
ml pro/
├── CarPrice.csv       ← raw dataset
├── lr_model.json      ← trained model (coefficients)
├── report.html        ← interactive dashboard
├── README.md          ← project overview
└── PLAN.md            ← this file
```

---

## 🔑 Key Learnings

1. **Data cleaning** — extracting brand from messy car names
2. **Encoding** — converting categorical text to numbers for the model
3. **Scaling** — StandardScaler ensures all features have equal weight
4. **Linear Regression** — learns a straight-line relationship between features and price
5. **Evaluation** — R² of 0.84 means the model explains 84% of price variance
6. **Deployment** — exporting model coefficients to JSON allows running predictions in pure JavaScript

---

*My First ML Project — Made with IBM Bob*
