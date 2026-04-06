# 🚗 Driving Style Risk Analysis #

## 📌 Overview

This project analyzes driver behavior using machine learning and clustering techniques.  

The objective is to identify distinct driving patterns and classify drivers into meaningful categories based on their behavior.  

Drivers are segmented into the following groups:
- **Eco Drivers** → Smooth and fuel-efficient driving style  
- **Moderate Drivers** → Balanced driving behavior  
- **Aggressive Drivers** → High-risk driving with sudden acceleration and braking  

## ⚙️ Methodology

- Data imported from CSV files  
- Performed feature engineering:
  - Aggression score calculation  
  - Jerk analysis (sudden acceleration/deceleration)  
- Applied **K-Means Clustering** to group driving styles  
- Used **Elbow Method** to determine optimal number of clusters  
- Applied **PCA (Principal Component Analysis)** for dimensionality reduction and visualization  


## 🛠️ Technical Workflow

- **Environment:** Google Colab / Python  
- **Algorithms Used:**
  - K-Means Clustering  
  - Principal Component Analysis (PCA)  
- **Optimization Techniques:**
  - Elbow Method (WCSS)  
  - Silhouette Analysis  
- **Verification:**
  - Statistical validation using Excel  
  - AVERAGEIF-based cross-checking  

## 📈 Insights

- Aggressive drivers show:
  - Higher jerk values  
  - Frequent sudden braking  

- Eco drivers exhibit:
  - Smoother acceleration patterns  
  - More stable driving behavior  

- Clear separation observed between clusters using PCA  

- Model can be effectively used for:
  - Usage-Based Insurance (UBI)  
  - Risk-based premium pricing  
## 📊 Visualizations (Links Only)

- 🟠 **Pie Chart – Driver Distribution**  
  Shows how drivers are divided into Eco, Moderate, and Aggressive categories based on clustering results.  
  [View Pie Chart](pie_chart.png)

- 🔵 **Bar Chart – Feature Comparison**  
  Compares key driving features such as speed, acceleration, and braking across different driver groups.  
  [View Bar Chart](bar_chart.png)

- 🟣 **Histogram – Aggression Score Distribution**  
  Displays how aggression scores are distributed among all drivers, helping identify overall driving behavior trends.  
  [View Histogram](histogram.png)

- 🟢 **PCA Plot – Cluster Visualization**  
  Visualizes the separation of driver clusters in reduced dimensions using Principal Component Analysis (PCA).  
  [View PCA Plot](pca.png)

- 🟡 **Elbow Curve – Optimal Clusters**  
  Helps determine the ideal number of clusters using the Elbow Method (WCSS).  
  [View Elbow Curve](elbow.png)

---

## 📄 Project Report

- **HTML Code (view source on GitHub)**  
  You can view the HTML file directly on GitHub to see all code used for the report.  
  [View Report Code](report.html)

- **Full Interactive Report (open in browser via GitHub Pages)**  
  Once GitHub Pages is enabled, this link will open your full report with all visualizations.  
  [Open Report](https://Keerthi45678.github.io/driving-style-risk-analysis/report.html)
