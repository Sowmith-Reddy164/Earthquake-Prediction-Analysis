# 🌍 Earthquake Prediction and Analysis

This project focuses on analyzing and predicting earthquake magnitudes using various regression models such as Ridge Regression, Decision Tree, and K-Nearest Neighbors (KNN). It includes interactive mapping of earthquake locations using `folium` and widgets for a more dynamic interface.

---

## 📁 Dataset

- **File:** `earthquake1.csv`
- The dataset contains details like latitude, longitude, date, time, depth, seismic magnitudes (`xm`, `ms`, `mb`, `richter`, etc.), and direction.

---

## 📌 Features

- 📍 **Interactive Earthquake Mapping** using `folium` and `ipywidgets`
- 📊 **Visual Data Analysis** using `seaborn`, `matplotlib`, and `plotly`
- 🧹 **Data Preprocessing**:
  - Missing value imputation
  - Label encoding for categorical variables
  - Feature scaling with MinMaxScaler
- 🤖 **Model Training**:
  - Ridge Regression
  - Decision Tree Regressor
  - K-Nearest Neighbors Regressor
- 📈 **Model Comparison**:
  - Accuracy metrics
  - Execution time visualization

---

## 📦 Required Libraries

Install the following Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn folium ipywidgets
