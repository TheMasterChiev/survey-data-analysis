# Survey Data Analysis: Education, Age, and Institutional Trust

This project explores how socio-demographic factors, specifically education and age, relate to institutional trust using survey data comparable to the European Social Survey (ESS).

The analysis focuses not only on identifying statistical relationships, but also on evaluating their practical significance through structured data analysis and interpretation.

---

## Overview

The analysis examines three key dimensions:

- Education (measured in years of education)  
- Age distribution  
- Institutional trust (measured as a composite scale based on trust in parliament, the legal system, and the police)  

By combining these variables, the project investigates how demographic characteristics relate to broader patterns of institutional trust.

---

## Methods and Approach

The project follows a structured exploratory data analysis (EDA) and modelling workflow:

- Data inspection and preparation  
- Data quality assessment (missing values analysis)  
- Distribution analysis (histograms and descriptive statistics)  
- Exploration of relationships (scatterplots and correlations)  
- Group comparisons across countries and demographics  
- Construction of a composite institutional trust scale  
- Reliability analysis (Cronbach’s alpha)  
- Linear regression modelling (OLS) to assess relationships between variables  

The analysis is implemented in a reproducible **Jupyter Notebook environment**.

---

## Key Findings

- Education and age are statistically significant predictors of institutional trust  
- However, their **practical impact is limited**, as indicated by a low R² value  
- Institutional trust is better understood as a **multifactorial concept**, influenced by a broader set of social and contextual variables  
- Combining multiple trust indicators into a composite scale provides a more robust measure than relying on a single variable  

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Repository Structure

- `notebooks/` — main analysis notebook  
- `figures/` — generated visualisations  
- `data/` — dataset (not included due to size)  

---

## Notes

This project is part of a broader effort to build a portfolio in data analysis, with a focus on research-oriented and statistically grounded applications.
