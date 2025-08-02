# Flight Delay Analysis & Prediction (2019–2023)

This repository contains a data analytics and machine learning project that explores **flight delays** in U.S. domestic aviation between 2019 and 2023. Using over **3 million flight records**, the analysis identifies delay patterns and builds predictive models to estimate the likelihood of a flight being delayed.

---

## Project Context

The project was built as a comprehensive deep dive into **why flights get delayed** and whether those delays can be **predicted**.  

Rather than just plotting raw delay counts, the analysis connects trends across **airlines**, **routes**, and **seasons** — and then transitions into predictive modeling using **Logistic Regression**, **Random Forest**, and **XGBoost**.

Key aspects of the project include:

- Cleaning and preparing a dataset of 3M flight records (2019–2023)  
- Conducting **EDA** on delay patterns by airline, airport, route, and month  
- Building predictive models for flight delay likelihood  
- Comparing **Random Forest** and **XGBoost** feature importance to understand model behavior  
- Creating clear visualizations for both insights and model results  

The aim was to turn raw aviation data into **actionable intelligence** for stakeholders like airlines, airports, and passengers.

---

## What's Included

- `aviation.ipynb`: Full Jupyter Notebook with analysis, visualizations, and commentary  
- `aviation.py`: Clean Python script version of the notebook workflow  
- `aviation_images/`: Exported plots (heatmaps, trend lines, feature importance charts)  
- `README.md`: Project overview and documentation  

---

## Modeling Overview

Three different machine learning models were implemented to predict delays:

- **Logistic Regression**: A simple, interpretable baseline model.  
- **Random Forest**: A tree-based model that captured nonlinear relationships but leaned heavily on departure time (44% importance).  
- **XGBoost**: A more sophisticated gradient boosting model that distributed importance more evenly across **airline**, **airport**, and **timing features**.

The comparison between Random Forest and XGBoost revealed **how different models “see” the data differently**, leading to richer insights.

---

## Metrics & Insights

The analysis covers both descriptive and predictive perspectives:

- **Descriptive:**  
  - Delay rates by airline and route  
  - Heatmap of delay-prone routes
  - Monthly and hourly delay rates
  - Airline-wise delay progression (60 months, 2019–2023)

- **Predictive:**  
  - Accuracy, precision, recall, and F1-score for each model  
  - Feature importance rankings  
  - Model behavior comparison (RF vs XGB)

---

## Visualizations

- **Matplotlib** bar charts for static comparisons (e.g., delay-prone airlines and routes)  
- **Seaborn** heatmaps for route-level delay patterns  
- **Plotly** interactive line charts for airline-wise delay trends  
- Side-by-side **feature importance bar plots** for Random Forest vs XGBoost  

---

## Contact

If you want to discuss the project, give feedback, or collaborate on future data/ML projects:  

- [LinkedIn](https://www.linkedin.com/in/aaditpahuja)  
- 📧 aaditpahuja@gmail.com
