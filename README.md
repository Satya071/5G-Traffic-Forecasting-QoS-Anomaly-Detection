# 5G-Traffic-Forecasting-QoS-Anomaly-Detection
Machine learning for 5G traffic forecasting and QoS anomaly detection


A Python-based machine learning project for forecasting 5G network traffic and detecting Quality of Service (QoS) anomalies using network performance data.

The system uses **XGBoost** for 24-hour-ahead traffic forecasting and **Isolation Forest** for anomaly detection, supporting proactive congestion monitoring and improved network reliability.

---

## Features

- 5G Network Traffic Forecasting (24-Hour Ahead)
- Machine Learning-Based Traffic Prediction
- QoS Anomaly Detection Using Isolation Forest
- Network Performance Analysis Across 3 Base Stations
- Analysis of Traffic Volume, Latency, Packet Loss, Throughput, and Signal Quality
- Forecasting Performance Evaluation Using MAE and RMSE
- Anomaly Detection Evaluation
- Data Visualization and Performance Analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Isolation Forest
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Project Structure

```text
5G-Traffic-Forecasting-QoS-Anomaly-Detection/
│
├── 5G_Traffic_Forecasting_QoS_Anomaly_Detection.ipynb
├── README.md
└── dataset/                 # Add if permitted and available
```

*Note: Update this structure to match the actual files in your repository.*

---

## Dataset Overview

The project analyzes network performance data containing:

- **504 hourly records**
- **3 base stations**
- Traffic volume and network quality indicators
- Latency and packet loss measurements
- Throughput and signal quality metrics

These features support traffic forecasting and the identification of abnormal network behavior.

---

## Machine Learning Models

### 1. XGBoost — Traffic Forecasting

XGBoost is used to predict network traffic 24 hours ahead based on historical traffic patterns and relevant network metrics.

**Evaluation Metrics:**
- Mean Absolute Error (MAE): **1.762 GB/hour**
- Root Mean Squared Error (RMSE): **2.229 GB/hour**

### 2. Isolation Forest — QoS Anomaly Detection

Isolation Forest identifies unusual network behavior that may indicate congestion or degradation in service quality.

**Observed Result:**
- Known anomalies detected: **2 out of 3**
- Anomaly detection rate: **66.7%**

---

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/5G-Traffic-Forecasting-QoS-Anomaly-Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd 5G-Traffic-Forecasting-QoS-Anomaly-Detection
```

### 3. Install Dependencies

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn jupyter
```

### 4. Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, upload the notebook to **Google Colab** and execute the cells in sequence.

---

## Results and Applications

The project combines predictive analytics and anomaly detection to support:

- Early identification of potential network congestion
- Monitoring of network performance and QoS indicators
- Data-driven network capacity planning
- Proactive investigation of abnormal network conditions
- Improved visibility into 5G network performance

---

## Future Improvements

- Evaluate models on larger, real-world 5G network datasets
- Improve forecasting accuracy using additional time-series models
- Enhance anomaly detection with more labeled events
- Develop a real-time network monitoring dashboard
- Integrate automated alerts for network performance degradation
- Extend analysis to more base stations and traffic scenarios

---

## Author

**SATYA MISHRA**

B.Tech — Electrical Engineering

Madan Mohan Malviya University of Technology(MMMUT)

GitHub : https://github.com/Satya071

LinkedIn: https://www.linkedin.com/in/satyamishra778

---
