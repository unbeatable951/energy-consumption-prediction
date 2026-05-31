# Energy Consumption Prediction

## Overview

This project predicts energy consumption using environmental and operational factors such as temperature, humidity, occupancy, HVAC usage, lighting usage, and renewable energy contribution.

The objective is to build a machine learning model that can estimate energy consumption and help optimize energy usage in buildings.

---

## Dataset Features

### Input Features

* Temperature
* Humidity
* SquareFootage
* Occupancy
* HVACUsage
* LightingUsage
* RenewableEnergy
* DayOfWeek
* Holiday

### Target Variable

* EnergyConsumption

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Model Saving using Joblib
8. Deployment using Gradio 

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Joblib

---

## Machine Learning Model

Current Model:

* Linear Regression

Saved Files:

* `linear_regression_energy_model.pkl`
* `energy_scaler.pkl`

---

## Repository Structure

```text
energy-consumption-prediction/
│
├── Energy_consumption.csv
├── Energy_consumption.ipynb
├── energy_scaler.pkl
├── linear_regression_energy_model.pkl
└── README.md
```

---

## Future Improvements

* Compare Linear Regression with Random Forest and XGBoost
* Hyperparameter Tuning
* Feature Importance Analysis
* Interactive Web Application
* Real-Time Energy Consumption Prediction

---

## Author

Diksha Singh

