# 🌾 Crop Yield Prediction Project

This project focuses on predicting crop yield (in tons/hectare) based on various agricultural and environmental factors using **Linear Regression** and **Decision Tree Regression**.

---

## 📌 Overview

- 🎯 **Objective**: Estimate the crop yield using machine learning techniques from historical agricultural data.
- 🔍 **Use Case**: Help farmers or agricultural planners make informed decisions based on regional conditions, soil type, rainfall, etc.

---

## 🧪 Dataset Details

- **File**: `crop_yield.csv`
- **Sample Features**:
  - `Region`: Region of cultivation (e.g., North, South, West)
  - `Soil_Type`: Sandy, Clay, Loam, etc.
  - `Crop`: Crop type such as Wheat, Cotton, Rice, etc.
  - `Rainfall_mm`: Average rainfall in mm
  - `Temperature_Celsius`: Avg temperature during growing season
  - `Fertilizer_Used`: Whether fertilizer was applied (TRUE/FALSE)
  - `Irrigation_Used`: Whether irrigation was used (TRUE/FALSE)
  - `Weather_Condition`: Cloudy, Rainy, Sunny
  - `Days_to_Harvest`: Number of days until harvest
  - `Yield_tons_per_hectare`: Target variable (crop productivity)

---

## 🛠️ Models Used

| Model                  | Description                                |
|------------------------|--------------------------------------------|
| Linear Regression      | Suitable for linear trend estimation       |
| Decision Tree Regression | Captures non-linear relationships         |

All preprocessing, model training, and evaluation are done in:  
📄 `Models/BTL_ML.ipynb`

---

## ⚙️ Project Structure
```
Crop_Yield_Prediction_Project/
│
├── Dataset/
│ └── crop_yield.csv # Main dataset
│
├── Models/
│ └── BTL_ML.ipynb # Notebook with model logic
│
└── README.md # Project documentation
```
---

## 📈 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## 🧠 Example Use Cases

- Forecast yield for different crops under varying conditions
- Compare impact of fertilizer and irrigation on yield
- Analyze crop performance in different weather conditions

---
