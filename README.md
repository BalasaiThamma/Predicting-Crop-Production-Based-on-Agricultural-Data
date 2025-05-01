# Predicting-Crop-Production-Based-on-Agricultural-Data

# 🌾 Crop Production Prediction App

This Streamlit web app predicts **crop production (in tons)** based on user-input features like **area harvested, yield, and year**, using real agricultural data from the FAO.

---

## 📌 Problem Statement

Accurate crop production prediction is essential for food security, supply chain planning, and policymaking. This project aims to:

- Analyze historical agricultural data to extract meaningful insights.
- Predict total crop production using machine learning models.
- Provide a simple and interactive web application for users to input data and get predictions.

---

## 📂 Dataset

- Source: FAOSTAT (UN's Food and Agriculture Organization)
- File: `FAOSTAT_data.xlsx`
- Format: Excel (.xlsx)
- Key columns used:
  - Area
  - Item (Crop Type)
  - Year
  - Element (Area harvested, Yield, Production)
  - Value

---

## ⚙️ Features

- 📈 Predicts crop production using:
  - Linear Regression
  - Random Forest Regressor
- 📊 Model evaluation with R², MAE, and MSE
- 📉 Interactive visualizations:
  - Yield vs Production scatter
  - Yearly trend line plot
  - Correlation heatmap
- 🔍 Region and crop type filtering


