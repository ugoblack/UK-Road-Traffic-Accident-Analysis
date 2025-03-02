# 🚗 UK Road Traffic Accident Analysis (2020) 📊  

This project analyzes **road traffic accident patterns in the UK (2020)** using **machine learning and data mining techniques**. The goal is to identify accident hotspots, risk factors, and trends to improve road safety.

---

## 🔍 **Project Overview**
- **Dataset**: UK Government Road Traffic Accident Database (2020)
- **Objectives**:
  - Clean & preprocess accident data.
  - Identify accident hotspots & patterns.
  - Use **machine learning models** to predict accident severity.
  - Perform **clustering analysis** to group accident locations.
  - Apply **anomaly detection** to find unusual accident cases.

---

## 🚀 **Key Findings**
### 📅 **Accident Trends**
- **Peak Time:** **3 PM - 6 PM** (highest at **5 PM**).
- **Most Dangerous Day:** **Friday (16.3% of accidents)**.
- **Motorcycle Accidents:** High-risk at **5 PM & 11 AM**.
- **Pedestrian Accidents:** High during **rush hours (7 AM - 9 AM, 3 PM - 6 PM)**.

### 🏆 **Model Performance**
| Model            | Training Accuracy | Test Accuracy | Cross-Validation |
|-----------------|------------------|--------------|------------------|
| **Random Forest** | 99%              | 99%          | 99%              |
| **Gradient Boost** | 94%              | 94%          | 93%              |
| **Logistic Regression** | 75%              | 73%          | 72%              |

- **Random Forest performed best for accident severity prediction**.

### 🔢 **Clustering Results**
| Clustering Algorithm | Silhouette Score |
|----------------------|-----------------|
| **KMeans**          | **0.6223**       |
| KMedoids            | 0.4342           |
| DBSCAN              | 0.3376           |

- **KMeans clustering was the best approach** for grouping accident locations.

### 🚨 **Anomaly Detection**
- Used **Isolation Forest & Local Outlier Factor** to identify accident **outliers**.
- Found anomalies in **urban and less populated areas**.

---

## 🛠 **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - Data Processing: `pandas`, `numpy`, `scipy`
  - Machine Learning: `scikit-learn`, `XGBoost`
  - Clustering: `KMeans`, `DBSCAN`
  - Anomaly Detection: `IsolationForest`, `LocalOutlierFactor`
  - Visualization: `Matplotlib`, `Seaborn`, `Folium` (for mapping)

---

## 📂 **Project Structure**
├── UK-Road-Traffic-Accident-Analysis.ipynb # Jupyter Notebook with implementation
├── UK-Road-Traffic-Accident-Analysis.pdf # Detailed report with findings 
├── README.md # This file


---

## 🔧 **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/ugoblack/UK-Road-Traffic-Accident-Analysis.git
2. Install dependencies
   pip install -r requirements.txt
3.Open the Jupyter Notebook
  jupyter notebook UK-Road-Traffic-Accident-Analysis.ipynb

