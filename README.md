# 🌍 CO₂ Emissions Forecasting using Machine Learning

This repository contains the full workflow and codebase for a machine learning project developed as part of the **AICTE-Shell AI for Climate Internship (Cycle 1, June 2025)**.

The goal is to forecast **CO₂ emissions per capita** based on country-specific factors like energy consumption, economic performance, land use, and population trends — using publicly available historical data from the World Bank.

---

## 📌 Project Overview

Climate change is a global crisis, with CO₂ emissions being one of its primary drivers. This project aims to provide a **data-driven solution** by:

- Predicting **CO₂ emissions** using machine learning based on socio-economic and environmental indicators.
- Helping policymakers and stakeholders understand future emission trends for better climate action.
- Applying **robust ML techniques** to screen, process, and analyze large-scale open-source climate data.

---

## 🗂️ Dataset Summary

- **Source:** [World Bank Climate Change Data](https://datacatalog.worldbank.org/dataset/climate-change-data)
- **Format:** Excel (`.xls`)
- **Time Range Used:** **1990 to 2011**
- **Countries Analyzed:** USA, India, Pakistan, Russia, New Zealand
- **Key Features:**
  - CO₂ emissions per capita
  - Energy use per capita
  - GNI per capita
  - GDP, FDI (% of GDP)
  - Population growth & urbanization
  - Cereal yield, protected area coverage

---

## ⚙️ Tech Stack

- **Language:** Python  
- **IDE:** Visual Studio Code  
- **Libraries Used:**
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning models & evaluation
  - `Streamlit` – (Optional) Deployment of predictions
  - `Jupyter Notebook`, `Colab` – Interactive development
  - `Excel/CSV` – Input data formats

---

## 📈 Project Workflow

### 1. 🔧 Data Preparation
- Imported `.xls` dataset and cleaned missing values.
- Selected relevant columns for modeling.
- Handled randomness using `random_state` and `np.random.seed`.

### 2. 🔍 Data Exploration (EDA)
- Explored data distributions and yearly trends.
- Created correlation heatmaps and grouped visualizations by year.
- Analyzed key patterns across countries.

### 3. 🤖 Model Building
- Used **Random Forest Regressor** from scikit-learn.
- Applied **Recursive Feature Elimination (RFE)** for feature selection.
- Performed **Cross-Validation (CV)** for robust training.
- Tuned hyperparameters using **GridSearchCV**.

### 4. 📊 Prediction & Forecasting
- Calculated **CAGR** for features over 1991–2008.
- Simulated feature growth year-by-year from **2010 to 2030**.
- Used trained model to forecast **CO₂ emissions per capita**.
- Visualized future trends via line plots per country.

---

## 🎯 Goals

- Predict future carbon emissions based on historical patterns.
- Understand the role of socio-economic indicators in climate trends.
- Empower decision-makers with **AI-powered environmental insights**.
- Build scalable models for **green forecasting and sustainability planning**.

---

## 🙌 Credits

- **Internship Program:** AICTE x Shell Green Skills & AI for Climate Internship  
- **Data Provider:** [World Bank Open Data – Climate Change Dataset](https://datacatalog.worldbank.org/dataset/climate-change-data)  
- **Mentorship & Guidance:** Internship mentors and program leads

---

## 📄 License

This project is developed for educational and research purposes under the AICTE-Shell Internship Program.  
Data is sourced from the World Bank under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

---
