# Air Quality Index (AQI) Prediction using Machine Learning

## Project Overview
Air pollution is a serious environmental and public health issue. This project focuses on predicting the Air Quality Index (AQI) using machine learning regression models based on pollutant concentration data from major Indian cities.

## Dataset
The dataset used is **Air Quality in Major Indian Cities**, sourced from Kaggle.  
It contains daily pollutant values such as PM2.5, PM10, NO2, SO2, CO, O3 along with AQI.

## Approach
- Data cleaning and preprocessing
- Feature engineering (date-based features)
- Handling missing values
- Model building using:
  - Linear Regression
  - Random Forest Regressor
- Model evaluation using RMSE, MAE, and R² metrics

## Results
Random Forest Regressor achieved better performance compared to Linear Regression with lower error values and higher R² score.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Future Improvements
- Include weather parameters
- Try advanced models like XGBoost
- Deploy the model as a web application
