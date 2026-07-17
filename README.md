# 🌍 AQI Prediction using Machine Learning
### Air Quality Index Forecasting with Regression Models

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

---

# 📌 Overview

Air pollution has become one of the most significant environmental and public health concerns worldwide. Accurate prediction of the **Air Quality Index (AQI)** enables governments, environmental agencies, and citizens to make informed decisions regarding pollution control and public safety.

This project develops an end-to-end Machine Learning pipeline that predicts AQI using pollutant concentration data collected from major Indian cities. Multiple regression models are evaluated, and their performance is compared using standard regression metrics.

The project demonstrates the complete workflow of a regression-based machine learning system—from preprocessing raw environmental data to model training, evaluation, visualization, and deployment-ready model serialization.

---

# ✨ Features

- 📊 Air Quality Index Prediction
- 🧹 Automated Data Cleaning
- ⚙ Feature Engineering
- 📅 Date-based Feature Extraction
- 📈 Multiple Regression Models
- 📊 Model Performance Comparison
- 🔍 Feature Importance Analysis
- 📉 Prediction Visualization
- 💾 Model Serialization using Joblib

---

# 🏗 System Architecture

```

Air Quality Dataset
│
▼
Data Cleaning
│
▼
Missing Value Handling
│
▼
Feature Engineering
│
▼
Train-Test Split
│
▼
Data Preprocessing
│
▼
Regression Models
│
├── Linear Regression
│
└── Random Forest Regressor
│
▼
Model Evaluation
│
▼
Feature Importance
│
▼
Prediction Visualization
│
▼
Saved ML Model

```

---

# 🤖 Machine Learning Pipeline

### Dataset

The project uses the **Air Quality in Major Indian Cities** dataset containing daily pollutant measurements such as:

- PM2.5
- PM10
- NO
- NO₂
- NOx
- NH₃
- CO
- SO₂
- O₃
- Benzene
- Toluene
- Xylene
- AQI

---

### Data Preprocessing

- Missing Value Handling
- Date Feature Extraction
- One-Hot Encoding
- Median Imputation
- Feature Scaling
- Train-Test Split

---

### Models Evaluated

| Model | Purpose |
|---------|----------|
| Linear Regression | Baseline Regression |
| Random Forest Regressor | Primary Prediction Model |

---

# 📊 Results

| Metric | Linear Regression | Random Forest |
|---------|------------------:|--------------:|
| RMSE | 56.80 | **40.19** |
| MAE | 30.06 | **20.39** |
| R² Score | 0.824 | **0.912** |

Random Forest significantly outperformed Linear Regression by reducing prediction error while achieving a higher coefficient of determination.

---

# 📈 Visualizations

The project includes

- Feature Importance Analysis
- Actual vs Predicted Scatter Plot
- Model Performance Comparison

These visualizations help interpret model behavior and identify the most influential environmental factors affecting AQI.

---

# 🔍 Key Insights

The Random Forest model identified the following pollutants as the most influential predictors of AQI:

- PM2.5
- Carbon Monoxide (CO)
- Nitric Oxide (NO)
- PM10
- Ozone (O₃)

This aligns with known environmental indicators contributing to air quality deterioration.

---

# 🛠 Tech Stack

### Programming

- Python

### Machine Learning

- Scikit-learn
- Pandas
- NumPy

### Visualization

- Matplotlib

### Model Storage

- Joblib

---

# 📂 Project Structure

```

AQI-Prediction/
│
├── train.py
├── requirements.txt
├── models/
├── assets/
├── data/
├── README.md
└── Project_Report.pdf

```

---

# 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/AQI-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
python train.py
```

The trained model will automatically be saved as

```
aqi_rf_model.joblib
```

---

# 📸 Screenshots

Include screenshots such as

- Dataset Overview
- Feature Importance Plot
- Actual vs Predicted Scatter Plot
- Model Evaluation Results

---

# 📄 Project Report

A detailed project report containing the methodology, implementation details, experimental evaluation, and future scope is available in this repository.

📘 **Project_Report.pdf**

---

# 🔮 Future Improvements

- Integrate real-time AQI APIs
- Add weather parameters for improved prediction
- Hyperparameter Optimization using GridSearchCV
- Deploy as a Flask or Streamlit Web Application
- Incorporate Deep Learning Regression Models
- Explain predictions using SHAP values

---

# 👩‍💻 Author

**Himanshi Tanwar**

Bachelor of Computer Applications (AI & ML)

Interested in

- Machine Learning
- Environmental Analytics
- Predictive Modeling
- Data Science

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
