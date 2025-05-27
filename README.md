# 🌫️ Air Quality Prediction using Random Forest
## 📌 Project Overview
This Machine Learning project predicts **air quality categories** based on environmental and demographic features. 
The goal is to classify the air quality into four distinct levels:
- **Good**
- **Moderate**
- **Poor**
- **Hazardous**
Accurate air quality classification helps in raising public awareness and supporting environmental decision-making.

## 📁 Dataset Information
The dataset includes both **environmental** and **location-based** features such as:
- 🌡️ `Temperature`
- 💧 `Humidity`
- 🧪 `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`
- 🏭 `Proximity_to_Industrial_Areas`
- 👥 `Population_Density`
These features were used to predict the air quality category.

## 🧠 Machine Learning Approach

- **Model Used**: `Random Forest Classifier`  
- **Why Random Forest?** It handles high-dimensional data, reduces overfitting, and provides feature importance.

## 📊 Exploratory Data Analysis
To understand the data better, the following visualizations were used:
- Correlation heatmaps
- Feature distribution plots
- Class balance visualization
- Pollution levels across different environmental conditions

## 🧪 Model Evaluation
- ✅ **Confusion Matrix**: Visualized misclassifications and performance per category.
- ✅ **Classification Report**:
  - Precision
  - Recall
  - F1-Score
- ✅ **Feature Importance**: Identified which variables most influenced predictions.

## 🔍 Key Insights
- PM2.5 and PM10 are the most influential features in determining air quality.
- Locations near industrial areas with high population density are more likely to fall in "poor" or "hazardous" categories.
- Temperature and humidity show moderate impact.

