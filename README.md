# 🦟 Dengue Outbreak Surveillance & Prediction – Sri Lanka

## 📌 Project Overview

Dengue fever is a major public health concern in Sri Lanka, with recurrent outbreaks closely linked to climatic and seasonal patterns. This project develops an **end-to-end dengue surveillance and prediction system** by integrating **epidemiological case data** with **environmental variables** such as rainfall, temperature, and humidity.

The system aims to identify **high-risk districts (hotspots)**, analyze **seasonal trends**, and **forecast dengue outbreaks** using time-series and machine learning techniques. The final output includes **GIS-based risk maps** and **interactive visualizations** to support early warning and public health decision-making.

---

## 🎯 Objectives

* Analyze historical dengue case trends across Sri Lankan districts
* Study the relationship between climate variables and dengue incidence
* Identify dengue hotspot regions using spatial analysis
* Predict future dengue outbreaks using time-series and ML models
* Visualize trends, risks, and forecasts through maps and dashboards

---

## 🌍 Real-World Relevance

Sri Lanka experiences periodic dengue epidemics, often aligned with **monsoon seasons**. In 2017 alone, reported cases exceeded **186,000**, highlighting the need for proactive surveillance.

A data-driven early warning system can help:

* Public health authorities plan **vector control measures** (e.g., fogging)
* Improve **resource allocation**
* Raise **community awareness** before peak outbreak periods

---

## 📊 Data Sources

### Dengue Case Data

* **Ministry of Health – Epidemiology Unit (Sri Lanka)**
* Weekly / monthly dengue case counts by district
* Data extracted from epidemiological bulletins (PDF reports)

### Climate & Environmental Data

* Rainfall, temperature, and humidity data obtained from:

  * Global reanalysis datasets (e.g., ERA5, NASA POWER)
  * Meteorological data mapped to district-level coordinates

> ⚠️ All data used are **aggregated and anonymized**, ensuring no personal or sensitive information is included.

---

## 🏗️ System Architecture

```
Data Sources
   ↓
Data Collection (PDF scraping / CSV / APIs)
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis (EDA)
   ↓
Feature Engineering
   ↓
Predictive Modeling (Time-Series / ML)
   ↓
Hotspot Detection & GIS Mapping
   ↓
Visualization & Dashboard
```

---

## 🧰 Technologies & Tools

* **Programming:** Python
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Time-Series Modeling:** ARIMA, SARIMA, Prophet
* **Geospatial Analysis:** GeoPandas, Shapely
* **Visualization:** Matplotlib, Seaborn, Plotly
* **Dashboard:** Streamlit
* **Version Control:** Git, GitHub

---

## 📁 Project Structure

```
dengue-surveillance-sri-lanka/
│
├── data/
│   ├── raw/              # Original datasets (PDFs, CSVs)
│   ├── processed/        # Cleaned and merged datasets
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_modeling.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── models.py
│
├── visuals/              # Plots and GIS maps
├── dashboard/            # Streamlit application
├── report/               # Final project report
│
├── requirements.txt
├── README.md
```

---

## 🔍 Key Features

### 📈 Exploratory Data Analysis

* Temporal trends of dengue cases
* Seasonal and monsoon-based patterns
* Climate–dengue correlation analysis
* District-wise comparisons

### 🧠 Predictive Modeling

* Time-series forecasting of dengue cases
* Outbreak risk classification (Low / Medium / High)
* Lag-based and climate-aware feature engineering

### 🗺️ Spatial Analysis

* Identification of high-risk dengue hotspots
* District-level GIS maps
* Visual representation of outbreak risk distribution

### 📊 Visualization & Dashboard

* Interactive trend charts
* Dengue incidence maps
* Forecasted outbreak alerts

---

## 📏 Model Evaluation

* **Forecasting Metrics:** RMSE, MAE
* **Classification Metrics:** Accuracy, Recall (emphasized due to public health importance)

---

## ⚖️ Ethical Considerations & Limitations

* Possible under-reporting of dengue cases
* Delays in official reporting
* Climate data granularity limitations
* No use of individual-level or sensitive health data

---

## 🚀 Future Enhancements

* Incorporate population density and mobility data
* Extend prediction horizon (3–6 months)
* Integrate real-time data pipelines
* Mobile-based alert system for communities

---

## 👩‍💻 Author

**Sawani Weerathunga**

* GitHub: https://github.com/SawaniD-Weerathunga
* LinkedIn: https://www.linkedin.com/in/sawani-weerathunga-507a55348/

---

## 📜 License

This project is intended for **academic and research purposes** only.
