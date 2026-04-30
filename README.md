# 🐟 Matsya – Ocean Hazard Analytics

> **A data-driven analytical platform empowering fishermen and marine authorities with intelligent insights for sustainable and profitable fishing operations**


## 🌊 Overview

**Matsya** is an AI-powered ocean analytics platform that uses **Machine Learning**, **Computer Vision**, and **Business Analytics** to revolutionize India's fishing industry by providing:

- 🔍 Automated fish species identification
- 💰 Market price prediction based on fish size
- 📍 Optimal fishing zone recommendations
- 📊 Data-driven insights for sustainable fishing

---

## 🎯 Problem Statement

India's fishing industry faces critical challenges:
- ❌ Unpredictable fish availability
- ❌ Inaccurate price estimation
- ❌ Limited access to profitable fishing zone data
- ❌ Lack of automated fish identification systems

**Matsya** addresses these challenges through intelligent data mining and predictive analytics.

---

## ✨ Key Features

### 🐠 Fish Classification Module
- CNN-based classification model for accurate fish species identification
- Real-time image processing from fishermen's captures

### 📏 Size Detection & Price Prediction
- **YOLOv8** object detection for fish size estimation
- Price prediction using 10+ years of Indian fish market data
- Regression analytics for market price forecasting

### 📈 Business Analytics Dashboard
- Seasonal fish availability trends
- Price fluctuation patterns
- Optimal fishing zone identification
- Region-wise profitability analysis

#### Key Features
- 🔍 Precision Fish Search: Real-time targeting engine that allows fishermen to search for specific species (e.g., Pomfret, Mackerel) and recalibrate the maritime heatmap instantly.
- 📡 Offshore Navigation Engine: A fully localized navigation system that provides turn-by-turn guidance, live ETA, and distance tracking using hardware GPS—functional even without internet deep at sea.
- 🧭 Smart Compass & Steering: Integrated Magnetometer sensor logic that offers a live rotating steering guide, showing the exact bearing and direction to the chosen fishing zone.
- 🔥 Dynamic Heatmap & Zone Ranking: Automatically identifies and ranks fishing zones based on catch probability, travel distance, and fuel efficiency.
- ⛽ Fuel & Cost Estimator: Real-time calculation of fuel requirements and trip costs (INR) for each zone to ensure profitable fishing expeditions.
<p align="center">
## 📸 App Screenshots

| Signup| Login | Home Screen| Analytics Page |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/0f8b92de-12a0-4722-b0f7-3e5f8bb52a26" width="250" alt="Auth & Google Login" /> | <img src="https://github.com/user-attachments/assets/0bb8473e-94bd-458a-87d9-fe8ca629fab1" width="250" alt="Home Screen" /> | <img src="https://github.com/user-attachments/assets/b14db27b-fca7-48c4-84a6-348dd6e675db" width="250" alt="Library View" /> | <img src="https://github.com/user-attachments/assets/2d1337b5-9008-487c-b74a-74b4671663c2" width="250" alt="Create Page" /> |
| **Catch Log Page** | **Alerts Page with notifications** | **Dynamic HeatMap** | **Most Probable Fish with Guidance** |
| <img src="https://github.com/user-attachments/assets/653144b4-ca7a-4504-9b58-f6a7bc4945c4" width="250" alt="Summary Page" /> | <img src="https://github.com/user-attachments/assets/7a4a9d77-c798-4d08-8fba-64e583ca30c6" width="250" alt="Interactive Quiz" /> | <img src="https://github.com/user-attachments/assets/8792ff5d-0936-4b4a-97fe-3e722e0a0e32" width="250" alt="User Profile" /> | <img src="https://github.com/user-attachments/assets/33d00605-a848-4197-9353-bef1b7798259" width="250" alt="Forgot Password (OTP)" /> |
</p>






---

## 🏗️ System Architecture

```mermaid
graph TD
    A[Fishermen Upload Image] --> B[Fish Classification Module]
    B --> C[YOLOv8 Detection]
    C --> D[Size Estimation]
    D --> E[Price Prediction]
    E --> F[Analytics Dashboard]
    F --> G[Actionable Insights]
```
---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Programming** | Python,JavaScript, React Native Expo |
| **ML Framework** | TensorFlow, Keras, CNN |
| **Object Detection** | YOLOv8 |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Power BI, Tableau |
| **Analytics** | Clustering, Regression Analysis |
| **Datasets** | Government Fisheries Data, Kaggle |

---

## 🔗 Live Services

### 🌐 Backend Services

- **ML Model Service**: [https://mlservice-146a.onrender.com/](https://mlservice-146a.onrender.com/)
- **Backend API**: [https://hackcelestial-kdg.onrender.com/](https://hackcelestial-kdg.onrender.com/)
- **Analytics Service**: [https://hackcelestial-kdg-1.onrender.com/](https://hackcelestial-kdg-1.onrender.com/)

### 📊 Analysis API Endpoints

#### Summary Analytics:
https://hackcelestial-kdg-1.onrender.com/api/catches/summary/68cda34fbedae2fb5e505890

#### Weekly Catch Data:
https://hackcelestial-kdg-1.onrender.com/api/catches/weekly/68cda34fbedae2fb5e505890


#### Species Distribution:
https://hackcelestial-kdg-1.onrender.com/api/catches/species/68cda34fbedae2fb5e505890


---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
TensorFlow 2.x
YOLOv8
Pandas, NumPy
```

## 💼 Business Impact

| Stakeholder | Benefits |
|------------|----------|
| **Fishermen** | Informed decisions on what, where, and when to fish for maximum returns |
| **Market Traders** | Improved price forecasting and inventory management |
| **Marine Authorities** | Enhanced understanding of fish population trends and overfishing patterns |

---

## 🎯 Results

✅ High accuracy in fish species classification  
✅ Efficient size detection using YOLOv8  
✅ Minimal error in price prediction vs. actual market rates  
✅ Region-wise profitability patterns identified  
✅ Comprehensive visual dashboards for decision-making  

---

## 🔮 Future Enhancements

- 🛰️ Real-time satellite data integration
- 📱 Mobile application for on-field usability
- 🌍 Multi-language support for regional fishermen
- ⚡ Real-time weather and ocean condition alerts

---

## 📚 References

1. [Government of India – National Fisheries Data Portal](https://fisheries.gov.in/)
2. [Kaggle Fish Species Dataset](https://www.kaggle.com/)
3. [Ultralytics YOLOv8 Documentation](https://docs.ultralytics.com/)
4. [FAO Fisheries and Aquaculture Statistics](http://www.fao.org/fishery/en)

