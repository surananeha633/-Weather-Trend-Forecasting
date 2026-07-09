# 🌦️ Weather Trend Forecasting

## 📌 Project Overview

This project analyzes global weather data to identify weather patterns and forecast future temperature trends using time series forecasting techniques. The project includes data cleaning, exploratory data analysis (EDA), visualization, anomaly detection, multiple forecasting models, feature importance analysis, and geographical weather analysis.

This project was completed as part of the **PM Accelerator Technical Assessment**.

---

## 🎯 Objectives

- Clean and preprocess the weather dataset.
- Perform Exploratory Data Analysis (EDA).
- Forecast future weather trends using the `last_updated` feature.
- Compare multiple forecasting models.
- Detect weather anomalies.
- Analyze climate and air quality patterns.
- Visualize geographical weather distributions.
- Evaluate forecasting model performance.

---

## 📊 Dataset

**Dataset:** Global Weather Repository

Source:
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository

The dataset contains daily weather information for cities around the world, including:

- Temperature
- Humidity
- Wind Speed
- Pressure
- Rainfall
- Air Quality
- UV Index
- Latitude & Longitude
- Sunrise & Sunset
- Moon Phase
- and many other weather-related features.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Prophet
- XGBoost
- Plotly
- SHAP

---

## 📂 Project Structure

```
Weather-Trend-Forecasting/
│
├── data/
│   └── Global Weather Repository.csv
│
├── notebooks/
│   └── Weather_Trend_Forecasting.ipynb
│
├── outputs/
│   ├── temperature_distribution.png
│   ├── heatmap.png
│   ├── forecast.png
│   ├── anomaly_detection.png
│   ├── feature_importance.png
│   └── spatial_analysis.png
│
├── report/
│   └── Weather_Trend_Report.pdf
│
├── presentation/
│   └── Weather_Trend_Presentation.pptx
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Removed duplicate records
- Converted date columns into datetime format
- Handled outliers using the IQR method
- Normalized numerical features
- Prepared the dataset for time series forecasting

---

## 📈 Exploratory Data Analysis

EDA includes:

- Temperature distribution
- Humidity analysis
- Rainfall trends
- Correlation heatmap
- Monthly weather trends
- Country-wise average temperature
- Weather condition frequency
- Air quality analysis

---

## 🤖 Forecasting Models

The following forecasting models were implemented:

- ARIMA
- Prophet
- XGBoost Regression

The models were compared using evaluation metrics, and an ensemble approach was explored to improve prediction accuracy.

---

## 🔍 Advanced Analysis

The project also includes:

### Anomaly Detection

- Isolation Forest

### Climate Analysis

- Long-term temperature trends
- Monthly weather variations

### Environmental Impact

- Air Quality Index analysis
- PM2.5 and PM10 correlation

### Feature Importance

- Random Forest Feature Importance
- SHAP Value Analysis

### Spatial Analysis

- Geographic visualization using latitude and longitude

### Geographical Comparison

- Weather comparisons across countries and regions

---

## 📊 Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

---

## 💡 Key Insights

- Identified global temperature trends over time.
- Compared weather conditions across countries.
- Observed relationships between humidity, rainfall, and air quality.
- Detected unusual weather events using anomaly detection.
- Compared forecasting model performance.
- Visualized geographical weather patterns.

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Weather-Trend-Forecasting.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open the notebook

```bash
jupyter notebook
```

Run:

```
Weather_Trend_Forecasting.ipynb
```

---

## 📦 Requirements

Install all required libraries using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- LSTM-based forecasting
- Transformer models for time series prediction
- Real-time weather API integration
- Interactive dashboard using Streamlit or Dash
- Automated model retraining pipeline

---

## 🎥 Demo

A short demo video explaining the project and results is included in the submission.

---

## 🙏 PM Accelerator Mission

This project was completed as part of the PM Accelerator Technical Assessment. The report and presentation include the PM Accelerator mission as requested in the assessment guidelines.

---

## 👩‍💻 Author

**Neha Surana**

