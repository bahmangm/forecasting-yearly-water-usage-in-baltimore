# 💧 Forecasting Yearly Water Usage in Baltimore

This project focuses on time series forecasting of **yearly water usage** in Baltimore using classical statistical modeling techniques. The goal is to analyze historical usage patterns and build predictive models to estimate future consumption—supporting infrastructure planning and environmental policy decisions.

---

## 📘 Project Background

This work follows the structured methodology presented in:

**_“Introduction to Time Series Forecasting with Python: How to Prepare Data and Develop Models to Predict the Future” by Jason Brownlee_**

The notebook applies the book’s core principles in a practical setting, progressing through data preparation, visualization, model evaluation, and long-term forecasting.

---

## 🛠️ Techniques & Tools Used

- **Data Preprocessing & Cleaning**
- **Time Series Decomposition**
- **Stationarity Checks (ADF Test)**
- **Differencing for Trend Removal**
- **Autocorrelation & Partial Autocorrelation Analysis**
- **ARIMA Model Development**
- **Model Diagnostics & Forecasting**
- **Error Evaluation (MAE, RMSE)**

**Libraries:**
- `pandas`, `numpy`
- `matplotlib`
- `statsmodels`
- `scikit-learn`
- `xgboost` (used for comparative modeling)
- `Amazon's time series forecasting model` (used for comparative modeling)

---

## 🔍 Key Features

- Loads and visualizes long-term yearly water usage trends
- Tests and enforces data stationarity using differencing and ADF
- Applies both classical statistical and gradient boosting models
- Evaluates forecast accuracy using robust error metrics
- Demonstrates how SARIMA can be used for yearly data forecasting

---

## 🧠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bahmangm/forecasting-yearly-water-usage-in-baltimore.git
   cd forecasting-yearly-water-usage-in-baltimore
   ```

2. Open the notebook in Jupyter:
   ```
   Forecasting_Yearly_Water_Usage_in_Baltimore.ipynb
   ```

3. Run each cell sequentially to see the analysis and forecasts.

---

## 📁 Dataset

- **Source:** [Data Set](https://raw.githubusercontent.com/jbrownlee/Datasets/refs/heads/master/yearly-water-usage.csv) 
- **Focus:** Annual water consumption data for Baltimore spanning several decades.

---

## 📌 Why This Matters

Understanding and forecasting water usage helps urban planners, environmentalists, and policy makers:

- 📍 Anticipate infrastructure needs
- 🚔 Support sustainability goals
- 🏙️ Optimize resource allocation

---

## 📊 Sample Output

Plots generated include:

- Line plots of yearly trends
- ACF & PACF plots
- Differenced series plots
- SARIMA model diagnostics
- Forecast visualizations with prediction intervals

---

## ✅ Status

✔️ Completed exploratory and predictive analysis  
🔄 Future enhancements may include SARIMA tuning, seasonal decomposition, or hybrid ML models.

---

## 📚 Acknowledgment

This project structure is inspired by the techniques outlined in:

**Jason Brownlee** – *"Introduction to Time Series Forecasting with Python: How to Prepare Data and Develop Models to Predict the Future"*
