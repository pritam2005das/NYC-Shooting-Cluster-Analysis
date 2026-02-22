# 📍 NYC Shooting Cluster Analysis

This project analyzes firearm shooting incidents in **New York City** using historical NYPD data.  
It applies **data preprocessing, clustering techniques, and visualization methods** to identify spatial hotspots and temporal patterns in shooting incidents.

The project includes:
- 📊 Data cleaning and exploratory data analysis  
- 🤖 Clustering model for hotspot detection  
- 📈 Power BI dashboard for interactive insights  
- 📑 Presentation summarizing findings  

---

## 📌 Objective

The primary objective of this project is to:

- Analyze historical shooting incident data across NYC boroughs  
- Identify geographic **hotspot clusters** using machine learning  
- Study time-based trends (yearly, monthly, hourly patterns)  
- Build a structured dashboard for crime pattern visualization  

---

## 📊 Dataset

- **Source:** NYPD Shooting Incident Data (Historic)  
- **Coverage:** Multiple years of NYC firearm shooting records  
- **Type:** Incident-level structured dataset  

### Key Features:
- Borough  
- Incident Date  
- Incident Time  
- Latitude  
- Longitude  
- Victim-related attributes  

### Files:
- `NYPD_Shooting_Incident_Data__Historic_.csv` → Raw dataset  
- `NYPD_Shooting_Incident_Data__Historic_Cleaned.csv` → Cleaned dataset  

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** → Data preprocessing  
- **Matplotlib, Seaborn** → Exploratory Data Analysis  
- **Scikit-learn** → Clustering model development  
- **Power BI** → Dashboard visualization  
- **Pickle** → Model serialization  

---

## 🔄 Methodology

### 1️⃣ Data Preprocessing  
- Removed null and inconsistent records  
- Standardized date and time formats  
- Extracted year, month, and hour features  
- Prepared cleaned dataset for analysis  

Notebook: `Preprocessing_for_Dashboard.ipynb`

---

### 2️⃣ Exploratory Data Analysis (EDA)  
- Borough-wise shooting distribution  
- Yearly and monthly trend analysis  
- Time-of-day pattern visualization  
- Spatial distribution exploration  

---

### 3️⃣ Cluster Analysis  
- Applied clustering algorithms (e.g., K-Means)  
- Grouped incidents based on latitude & longitude  
- Identified recurring high-density shooting zones  

Notebook: `model.ipynb`  
Model saved as: `model.pkl`

---

## 📊 Dashboard

Power BI Dashboard: `NYPD_Shooting_Incident_Dashboard.pbix`

Includes:
- Borough-level shooting comparison  
- Yearly & monthly trend visualization  
- Time-based distribution analysis  
- Spatial cluster insights  

---

## 📁 Project Structure

**NYC-Shooting-Cluster-Analysis/**
- `NYPD_Shooting_Incident_Data__Historic_.csv`
- `NYPD_Shooting_Incident_Data__Historic_Cleaned.csv`
- `Preprocessing_for_Dashboard.ipynb`
- `model.ipynb`
- `model.pkl`
- `NYPD_Shooting_Incident_Dashboard.pbix`
- `NYC Shooting Cluster Analysis.pptx`
- `README.md`

- 🔗 **Project link:** [NYC-Shooting-Cluster-Analysis](https://github.com/pritam2005das/NYC-Shooting-Cluster-Analysis)
---

## 📈 Key Findings

- Certain NYC boroughs consistently show higher shooting frequencies.  
- Evening hours exhibit increased incident concentration.  
- Spatial clustering reveals persistent hotspot zones across years.  

---

## 🔮 Future Scope

- Integrate interactive geo-maps (Folium / Plotly)  
- Build predictive classification model for risk estimation  
- Deploy web-based dashboard for real-time monitoring  
- Add explainable AI techniques for cluster interpretation  

---

## 👨‍💻 Author

**Pritam Das**  
GitHub: https://github.com/pritam2005das
