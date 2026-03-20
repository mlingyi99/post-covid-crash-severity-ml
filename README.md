# Post-COVID Crash Severity Analysis using Machine Learning

This repository contains the code and analysis for the study:

**“Structural Shifts in Crash Severity Risk After COVID-19: An Interpretable Machine Learning Analysis of 20 Years of Pennsylvania Crash Data”**  

The study investigates how the COVID-19 pandemic fundamentally altered the determinants of severe traffic crashes using **interpretable machine learning** (Random Forest, XGBoost, and SHAP).

---
## Data

- **Source:** Pennsylvania Department of Transportation (PennDOT) Statewide Crash Database, 2005–2024  
- **Note:** Raw crash data is restricted and not included. Processed data supporting the analysis can be added here if permitted.  
- **Structure:**  
  - Aggregated at the crash level  
  - Features include:  
    - Behavioral flags: `SPEEDING`, `AGGRESSIVE_DRIVING`, `ALCOHOL_RELATED`, etc.  
    - Demographics: `avg_driver_age`, `pct_male`  
    - Contextual factors: `URBAN_RURAL`, `HOUR_OF_DAY`, `DAY_OF_WEEK`  

---

## Methods

- **Machine Learning Models:** Random Forest, XGBoost  
- **Interpretability:** SHAP (SHapley Additive exPlanations) for feature importance  
- **Objective:** Compare pre-COVID (2005–2019) and post-COVID (2022–2024) crash severity determinants  
- **Key Insights:**  
  - Driver age and temporal factors have increased importance post-COVID  
  - Traditional behavioral risk factors (speeding, alcohol, lane departures) declined in predictive power  
  - Highlights a shift toward demographic and contextual determinants of crash severity  

---

## Usage

1. Clone the repository:  
```bash
git clone https://github.com/<username>/post-covid-crash-severity-ml.git
