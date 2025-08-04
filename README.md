# 🌾 Food Security Data Analysis & Forecasting

## 📌 Overview

This repository contains an **Exploratory Data Analysis (EDA)** of the National Food Security Act (NFSA) Monthly Allocation, Transaction, and Foodgrain Distribution dataset.  
The primary goal of this project is to understand the distribution patterns, trends, and key relationships within the data to prepare for building a **predictive model** for food grain distribution.

The analysis focuses on several key metrics, including:
- Food grain allocation
- Ration card transactions
- Role of Aadhaar-based authentication across Indian states

---

## ✨ Key Findings

- **Clean Data**: The dataset was found to be complete with no missing values, allowing for direct analysis after minor preprocessing.
- **ePoS Dominance**: Electronic Point of Sale (ePoS) is the predominant method for food grain distribution, with manual distribution playing a minimal role.
- **Aadhaar Success**: Aadhaar-authenticated transactions showed rapid growth, stabilizing at over 90% in most states by late 2019.
- **COVID-19 Impact**: A sharp spike in food grain distribution was observed around mid-2020, likely due to pandemic relief measures.
- **Strong Seasonality**: Distribution volumes show consistent annual seasonality, peaking between April and June.

---

## 📊 Visualizations

### Distribution of Numerical Features

**Histograms and Box Plots** were used to visualize key variable distributions and detect skewness/outliers.

- **Histogram Plot**:  
  <img width="946" height="710" alt="image" src="https://github.com/user-attachments/assets/7f542713-b25b-4b09-9328-fbb07fcf2d21" />


- **Box Plot**:  
  <img width="946" height="710" alt="image" src="https://github.com/user-attachments/assets/25ccd84b-cb36-4e81-8c5d-8093421983a0" />


---

### Feature Correlation

A **correlation heatmap** revealed strong relationships between allocation, ePoS distribution, and total distribution.

- **Correlation Matrix Heatmap**:  
  <img width="946" height="866" alt="image" src="https://github.com/user-attachments/assets/2307ce77-be4c-4fa9-9244-f55fe9ac8145" />


---

### Time-Series Trends

**Line plots** helped identify national trends and the impact of events like the COVID-19 pandemic.

- **National Food Grain Distribution Over Time**:  
  <img width="946" height="405" alt="image" src="https://github.com/user-attachments/assets/13dd57db-83cf-4ec9-9a14-9b37d8c45bea" />


- **Aadhaar Authentication Trends Over Time**:  
  <img width="946" height="405" alt="image" src="https://github.com/user-attachments/assets/72325748-42c1-462f-991b-8b849f06c09e" />


---

### State-wise and Seasonal Patterns

Insights into:
- How different states adopted new systems
- Monthly distribution seasonality

- **State-wise Authentication Trends**:  
  <img width="946" height="473" alt="image" src="https://github.com/user-attachments/assets/822ca4a6-5636-4bf4-a595-9a66a0905b6c" />


- **Monthly Distribution Patterns**:  
  <img width="946" height="472" alt="image" src="https://github.com/user-attachments/assets/9e83b8d4-8848-4ac7-88a7-c94306105ddb" />



---

## 🔮 Future Work: Predictive Modeling

The next phase involves **time-series forecasting** to predict future food grain distribution (`Total_Distribution_MT`).

**Baseline Model: Random Forest Regressor**
- Handles non-linear relationships
- Robust to outliers
- Provides feature importance insights

**Next Steps**:
- Explore ARIMA or deep learning models for comparison

---
