<img width="979" height="730" alt="image" src="https://github.com/user-attachments/assets/abb846d3-bc68-4476-8739-92e7d698c91c" />

# Forecasting Regional Electricity Demand in Saudi Arabia

This repository contains the full, reproducible analysis supporting the article:

**“Forecasting Regional Electricity Demand in Saudi Arabia: An applied data science study using SARIMA and machine learning on open energy data.”**

The project examines regional electricity demand dynamics in Saudi Arabia using monthly load data and compares traditional time-series models with machine learning approaches.



## Overview

Electricity demand forecasting plays a critical role in system reliability, capacity planning, and energy policy design, particularly in cooling-dominated power systems such as Saudi Arabia. This project develops a transparent and regionally disaggregated forecasting framework using:

- Seasonal ARIMA (SARIMA) models as a statistical benchmark  
- Tree-based machine learning models to capture nonlinear and peak-driven behavior  

The analysis focuses on regional peak demand behavior rather than national aggregates.



## Data

- **Source:** KAPSARC Energy Data Portal  
- **Coverage:** Monthly regional electricity load, 2009–2019  
- **Regions:** Central, Eastern, Western, Southern  
- **Metric:** Monthly maximum (peak) load in gigawatts  

The dataset is publicly available through KAPSARC and is included here for research and educational purposes.



## Methods

- Exploratory data analysis and seasonal diagnostics  
- Feature engineering using lagged demand and calendar variables  
- Chronological train–validation–test split  
- Model evaluation using RMSE and MAPE  
- Cross-regional comparison of forecasting performance  



## Repository Structure

- `notebooks/` – Jupyter notebooks with full analysis  
- `data/` – Input dataset  
- `figures/` – Visualizations used in the article  
- `requirements.txt` – Python dependencies  



## Reproducibility

All code and results in this repository are fully reproducible.  
The notebooks are designed to run end-to-end using only publicly available data.



## License

This project is released under the MIT License.



## Author

Dr. Eskinder Belete  
Adjunct Professor of Data Science and AI  
