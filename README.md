🌍 Carbon Emission Prediction

A machine learning-based project to analyze and predict climate-related indicators using country-specific data.

📌 Project Overview

This project focuses on understanding the relationships between greenhouse gas emissions and various country-level factors like demographics, economy, land use, energy, and climate. The goal is to clean, transform, and analyze the dataset and build a machine learning model to predict emissions or related variables.

This work is part of the AICTE Internship – Cycle 1 (June 2025).


---

📊 Dataset Summary

Source: World Bank Climate Change Data

Type: Excel dataset with multiple country-level indicators

Rows: 3,954

Columns: 28

Includes data on: CO₂, CH₄, N₂O emissions, GDP, urban population, forest area, energy use, and more



---

📂 Project Structure

Carbon-Emission-Prediction/
│
├── data/
│   └── climate_change_download_0.xlsx
├── notebooks/
│   └── data_preparation.ipynb
├── .gitignore
├── README.md
└── requirements.txt


---

🔧 Workflow Summary

1. Data Cleaning & Preparation

Removed rows with 'Text' in "SCALE" and "Decimals" columns

Dropped unnecessary columns

Replaced ".." and empty strings with NaN

Converted data types to numeric

Restructured the dataset to country-year format


2. Feature Engineering

Renamed long feature names into short codes

Mapped units and cleaned data entries


3. Data Exploration & Analysis

Summarized trends in emissions and indicators

Explored correlations and patterns


4. Model Development (upcoming)

Build ML models to predict climate outcomes like CO₂ levels



---

🔮 Goals

Understand how country-level indicators influence emissions

Build a predictive ML model for climate-related forecasting

Enable better environmental planning using data insights



---

🚀 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Git & GitHub

Excel / CSV data files



---

🤝 Credits

AICTE Internship Program

World Bank Open Data
