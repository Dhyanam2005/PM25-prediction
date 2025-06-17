# 🌫️ PM2.5 Air Quality Prediction & Visualization in Delhi

This project aims to predict PM2.5 air pollution levels across various locations in Delhi using machine learning (Random Forest Regressor) and visualize actual vs. predicted values on an interactive map using Folium.

---

## 📊 Project Summary

- **Objective:** Predict PM2.5 levels at different monitoring stations in Delhi using meteorological and location-based features.
- **Data Sources:** Station-wise pollution data, meteorological variables, and geographical coordinates.
- **Model Used:** Random Forest Regressor
- **Tools:** `scikit-learn`, `pandas`, `folium`, `joblib`

---

## 🧠 Model Performance

| Metric       | Value        |
|--------------|--------------|
| R² Score     | 0.895        |
| RMSE         | ~595.91      |
| MAE          | ~13.91       |

---

## 🌍 Visualization

### Actual vs Predicted PM2.5 (India Map)

Blue dots represent **actual** PM2.5 values.  
Red dots (slightly offset) represent **predicted** PM2.5 values

![Map Preview](./preview_pm25_map.png)  
*(Or view full map here: [Open Map](./india_pm25_station_averages.html))*