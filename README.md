# Flambeau Hydropower Forecasting

Short-term hydroelectric power generation forecasting for Dairyland Power Cooperative’s **Flambeau Station** using river gauge height and weather data. Built as part of a **Quantitative Analyst Intern technical interview exercise**.

This project covers exploratory data analysis, feature relationships, model comparison, and a 7-day production forecast.

---

## Objective

Predict daily power generation (MW) for **Oct 24–30, 2025** using:
- Historical river gauge height
- Historical weather conditions
- Past Flambeau power output

---

## Repository Structure
data/ Raw historical and forecast datasets
figures/ All generated plots and model visualizations
notebooks/ Full end-to-end analysis and modeling notebook
presentation/ Interview presentation + original problem statement

---

## Data

- **Power Generation** – Historical MW output (2020–2025)
- **Gauge Height** – River height with forecasted values
- **Weather** – Temperature, precipitation, snowfall, snow depth

Missing values were cleaned, standardized, and aligned on a shared time index.

---

## Modeling Approach

- Feature engineering from hydrology and weather variables
- Model comparison:
  - Linear Regression
  - Random Forest Regression
- Performance evaluated using predicted vs. actual scatter analysis
- Feature importance extracted to quantify river height dominance

---

## Key Findings

- River gauge height is the dominant driver of power output
- Clear nonlinear saturation behavior at higher water levels
- Random Forest consistently outperformed linear regression at higher MW ranges
- Forecasted output for late Oct 2025 remains within historical seasonal norms

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Author

**Andrew Peirce**
Computer Science (Cybersecurity) – University of Wisconsin–La Crosse
Music Performance Minor
