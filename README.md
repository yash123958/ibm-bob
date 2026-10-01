# 🚗 Car Price Prediction — My First ML Project

A machine learning project that predicts car prices using **Linear Regression**, built on the CarPrice dataset with a fully interactive dark-themed HTML dashboard.

---

## 📁 Project Files

| File | Description |
|---|---|
| `CarPrice.csv` | Raw dataset — 205 cars, 26 features |
| `lr_model.json` | Trained Linear Regression model (coefficients + encoders + scaler) |
| `report.html` | Interactive dashboard — EDA charts + live price predictor |

---

## 📊 Dataset

- **205** car records
- **25** input features (engine size, horsepower, brand, body type, etc.)
- **Target variable:** `price` (USD)
- **Price range:** $5,118 – $45,400

---

## 🤖 Model

| Property | Value |
|---|---|
| Algorithm | Linear Regression |
| R² Score | 0.8411 |
| RMSE | $3,541.96 |
| MAE | $2,127.47 |
| Train / Test Split | 80% / 20% |

### Features Used
Symboling, fuel type, aspiration, door number, body style, drive wheel, engine location, wheelbase, car length, car width, car height, curb weight, engine type, cylinders, engine size, fuel system, bore ratio, stroke, compression ratio, horsepower, peak RPM, city MPG, highway MPG, brand.

---

## 🖥️ Dashboard (`report.html`)

Open `report.html` in any browser. It includes:

- **KPI strip** — dataset size, R² score, RMSE
- **Live Price Predictor** — fill in 24 car specs → instant price estimate
- **Price Distribution** chart
- **Average Price by Brand** chart
- **Horsepower vs Price** scatter plot
- **Actual vs Predicted** scatter plot (test set)

> No server needed — everything runs in the browser.

---

## 🚀 How to Use

1. Open `report.html` in your browser
2. Scroll to **Predict a Car Price**
3. Select/fill in the car specifications
4. Click **Predict Price**

---

## 🛠️ Tech Stack

- **ML:** Python, scikit-learn, pandas, numpy
- **Dashboard:** HTML, CSS, JavaScript
- **Charts:** Apache ECharts

---

*My First ML Project — Made with IBM Bob*
