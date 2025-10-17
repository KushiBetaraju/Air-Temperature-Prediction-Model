# 🌡️ Temperature Prediction Using Linear Regression

This project uses **machine learning** to predict air temperature based on meteorological data. A **Linear Regression** model is trained to estimate temperature and classify it as **“Hot”** or **“Not Hot”** using a 25 °C threshold.

---

## 📌 Features

- Data preprocessing and feature selection  
- Linear Regression model for temperature prediction  
- Regression + classification performance evaluation  
- Scatter plot visualization of Actual vs Predicted values  
- Real-time temperature prediction using user input  
- Overfitting check for model reliability

---

## 🧾 Dataset

- **Source:** `cleaned_weather.csv`  
- **Features used:**  
  `Tpot`, `Tdew`, `rh`, `VPmax`, `VPact`, `VPdef`, `rho`, `wv`, `max. wv`  
- **Target variable:** `T` (Air Temperature °C)

---

## 🧮 Model & Metrics

- **Model:** Linear Regression (Scikit-learn)  
- **Regression Metrics:** MSE, MAE, R² Score  
- **Classification Metrics:** Accuracy, Precision, Recall, F1 Score  
- **Visualization:** Actual vs Predicted Temperature Scatter Plot

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name

---

## Install Dependencies
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🧠 Future Improvements

-> Use advanced models like Random Forest or Deep Learning

-> Add feature importance analysis

-> Integrate OpenWeatherMap API for live data

-> Deploy as a simple web app

---

