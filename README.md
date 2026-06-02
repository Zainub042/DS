# 🌍 AQI Data Science Project

---

## 📊 Dataset
- **Dataset Name:** Global Urban AQI Dataset  
- **File:** `dataset/global_urban_aqi_dataset.csv`  
- **Description:** Contains AQI values and pollutant concentrations (PM2.5, PM10, CO, NO2, O3, SO2) along with meteorological features (Temperature, Humidity, Wind Speed) for multiple cities worldwide (2015–2025).  

---

## 📝 Problem Statement
Air pollution is a major global challenge.  
The goal of this project is twofold:  
1. **(Data Science):** Analyze AQI data, visualize pollution patterns, and apply machine learning models to classify and cluster air quality categories.  
2. **(Reinforcement Learning):** Train an RL agent to learn optimal traffic-control actions based on AQI states.  

---

## ⚙️ Tools and Libraries Used
- Python 3  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## 📈 DS Highlights
- Classification Models: KNN, Naive Bayes
- Clustering: K-Means (k=3)
- Dimensionality Reduction: PCA
- Visualizations: AQI distributions, pollutant correlations, clustering plots
- Key Findings: PM2.5 is the strongest driver of AQI; South Asian cities consistently show highest AQI values.

---

## 🤖 RL Traffic Control)
- States: Low, Medium, High AQI
- Actions: No Restriction, Partial Restriction, High-Pollution Alert
- Reward System: +10 for correct action, penalties otherwise
- Training: 500 episodes, α=0.1, γ=0.9, ε=0.2
- Final Q-table: Saved in outputs/rl_results/q_table.csv
- Learned Policy:
- Low AQI → No Restriction
- Medium AQI → Partial Restriction
- High AQI → High-Pollution Alert
  
---

## 📑 Reports

---

## 🚀 How to Run the Notebooks
1. Clone the repository:
   ```bash
   git clone https://github.com/Zainub042/DS.git
