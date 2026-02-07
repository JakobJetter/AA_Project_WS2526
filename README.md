# Analytics & Applications Project 2025/26 – Electric Vehicle (EV) Charging Analysis & Forecasting

## Project Overview

This project focuses on the analysis and prediction of electric vehicle (EV) charging utilization. It combines data preprocessing, exploratory data analysis, clustering techniques, and predictive modeling to better understand charging behavior and forecast future charging demand.

The project is structured into consecutive analysis stages, which should be executed in the order described below.

---

## How to Run

1. Clone the repository.
2. Make sure to install the environment AA_env_group4 or all of the required dependencies.
3. Open the Jupyter notebooks (in sequence) in the respective directories to explore the analysis and models

---

## Dependencies

  - python=3.10
  - notebook
  - ipykernel
  - jupyter_client
  - jupyter_core
  - numpy
  - pandas
  - scipy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels
  - sympy
  - pip

 **Note**: You can run all Notebooks on the AA_env_group4 Environment, which can be installed from - [`AA_env_group4`](environment.yml). For further Version Information see - [`Requirements`](requirements.txt)

---

## Project Structure & Workflow

### 1. Data Preparation

In this phase, raw data is cleaned, transformed, and enriched to ensure consistency and usability for subsequent analyses. This includes handling missing values, correcting data types, and integrating external data sources such as weather data.

**Notebooks**
- [`Data Preparation Charging Data`](01_Data_Preparation/data_preparation_charging_data.ipynb)
- [`Data Preparation Weather Data`](01_Data_Preparation/data_preparation_weather_data.ipynb)

---

### 2. Descriptive Analytics

Exploratory Data Analysis is performed to identify patterns, trends, and distributions in charging behavior. This step provides the analytical foundation for both clustering and predictive modeling.

**Notebooks**
- [`Key Performance Indicators (KPIs)`](02_Descriptive_Analytics/key_performance_indicators.ipynb)
- [`Site Characteristics`](02_Descriptive_Analytics/site_characteristics.ipynb)

---

### 3. Cluster Analysis

Clustering techniques are applied to group similar users and identify distinct user behavior patterns. The results support improved capacity planning and targeted programs.

**Notebook**
- [`Cluster Analysis`](03_Cluster_Analysis/clustering.ipynb)

---

### 4. Predictive Analysis

Predictive models are developed to forecast future charging utilization.

**Notebooks**
- [`Feature Engineering`](04_Predicitive_Analysis/feature_engineering.ipynb)
- [`Prediction Models`](04_Predicitve_Analysis/regression_models_and_neural_network.ipynb)

---

## Repository Structure

- `00_Productive_Data/`: Contains cleaned charging and weather data files
- `01_Data_Preparation/`:Contains raw charging and weather data files and notebooks for data preparation.
- `02_Descriptive_Analytics/`: Contains notebooks for descriptive analytics (Key Performance Indicators and Site Characteristics).
- `03_Cluster_Analysis/`: Contains notebook and results for cluster analysis.
- `04_Predicitve_Analysis/`: Contains notebooks and datasets for predictive analysis.
- `environment.yml`: Contains the environment with all necesarry dependencies.
- `requirements.txt`: Contains further information on versions.


---

## Notes

- The notebooks are designed to be executed sequentially.
- Results may vary slightly depending on hardware and random seeds.
- Computationally intensive steps (e.g., model training) may require sufficient system resources (and a lot of time).
