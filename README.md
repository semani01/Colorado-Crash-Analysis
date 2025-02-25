# **Colorado Crash Data Analysis with Machine Learning**
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

🚗 **Analyzing and Predicting Traffic Accidents in Colorado using ID3, Random Forest, Naïve Bayes, and Logistic Regression**

## **📌 Overview**
This project applies **machine learning models** to analyze **traffic accident data** from **Colorado (2007-2022)**. It aims to identify **patterns, correlations, and key risk factors** influencing **accident severity** using **ID3 Decision Tree, Random Forest, Naïve Bayes, and Logistic Regression**.

By leveraging **big data and predictive analytics**, this research helps **policy-makers, law enforcement, and insurance companies** make data-driven decisions to improve **road safety**.

---

## **📊 Dataset Details**
- **Source**: Colorado Department of Transportation (CDOT)
- **Timeframe**: 2007 - 2022
- **Total Records**: **1,627,682 accidents**
- **Features per Record**: **84 attributes** including:
  - 📍 **Location (Latitude, Longitude)**
  - 🕒 **Time of Accident**
  - 🌦️ **Weather Conditions**
  - 🚦 **Road & Lighting Conditions**
  - 🚗 **Vehicle Type & Movement**
  - 🏥 **Number of Injuries & Fatalities**
  - 🚓 **Driver Impairment (Alcohol/Drug Suspected)**


## **📌 Project Objectives**
- 🔍 **Identify accident-prone locations** and **temporal crash patterns**.
- 📊 **Analyze weather, road conditions, and driver behavior** as crash risk factors.
- 🏆 **Compare machine learning models** for predicting accident severity.
- 🚀 **Develop predictive models** for proactive road safety measures.


## **⚙️ Machine Learning Models Used**
| Model | Description | Key Features |
|--------|-------------|--------------|
| **ID3 Decision Tree** | Recursive decision-making structure | Fast, interpretable |
| **Random Forest** | Ensemble of decision trees | High accuracy, robust to noise |
| **Naïve Bayes** | Probabilistic classification | Best for categorical data |
| **Logistic Regression** | Statistical model for binary classification | Simple, interpretable |

🔹 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score  
🔹 **Data Processing**: One-Hot Encoding, Feature Engineering, Correlation Analysis  


## **📌 Exploratory Data Analysis (EDA)**
- **🗺️ Geospatial Analysis**: Identified accident hotspots using **heatmaps**.
- **📈 Time-Series Analysis**: Found peak accident times (rush hours).
- **🌦️ Weather Insights**: More accidents occur in **clear weather** due to **driver negligence**.
- **🚦 Road Conditions**: Higher crashes at **intersections & highways**.

## **📂 Project Structure**

📁 **Colorado-Crash-Analysis**  
│── 📜 **BDS Project - ID3, RF, NB, LR - Final.ipynb**  `# Jupyter Notebook with full code`  
│── 📜 **README.md**  `# Project Documentation`  
│── 📜 **requirements.txt**  `# Python dependencies`  


## **📌 Installation & Setup**
### **🔹 Prerequisites**
Ensure you have **Python 3.8+** and the required libraries installed.

### **🔹 Install Dependencies**
```bash
pip install -r requirements.txt
```


---


## **📌 Key Findings**
### **🚗 Crash Patterns**
- 🕒 **Most Accidents Occur in Daylight**, not nighttime.
- ❄️ **Bad Weather = More Severe Accidents**, but **Clear Weather = More Frequent Crashes**.
- 🛣️ **Urban Intersections = Highest Crash Rates**, rural roads have **fewer but deadlier crashes**.

### **🏆 Best Machine Learning Model**
| Model | Accuracy |
|--------|----------|
| **ID3 Decision Tree** | **99.95%** |
| **Random Forest** | **97.5%** |
| **Naïve Bayes** | **85.2%** |
| **Logistic Regression** | **78.4%** |


## **📌 Future Enhancements**
✅ **Real-time Data Integration** (Traffic Cameras, GPS, Weather APIs)  
✅ **Deep Learning Models** (LSTMs for time-series crash prediction)  
✅ **Deploy as a Web App** (Flask/Django-based dashboard for public use)  


## **📌 Contribution & Collaboration**
🤝 **Want to contribute?** Fork the repository and submit a **pull request**!  
📬 Contact: **saisrikar.emani@ucdenver.edu**  

---

## **📌 License**
📝 MIT License – Feel free to use and modify! 🚀  
