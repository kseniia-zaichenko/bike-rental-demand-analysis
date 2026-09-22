# Bike Rental Demand Analysis and Prediction

## About the Project
This project focuses on the exploratory data analysis (EDA) and predictive modelling of daily bike rental demand for the Rockhampton Regional Council[cite: 2]. The objective is to identify how seasonal and weather factors influence bike usage and to evaluate the feasibility of forecasting demand to assist in future urban planning, such as station expansion and bike availability[cite: 2].

## Repository Structure
* **`Code_by_Kseniia_Zaichenko_12264917.ipynb`**: Jupyter Notebook containing data cleaning, exploratory data analysis, and regression model development[cite: 2].
* **`bike_rental.csv`**: The dataset containing daily bike rental records[cite: 2].
* **`12264917-report.pdf`**: The comprehensive explanatory data analysis report including visualisations, evaluation metrics, and actionable recommendations.

## Key Findings
* **Best Performing Model:** The Random Forest Regressor outperformed the Linear Regression baseline, explaining approximately 87% (R² = 0.871) of the variance in daily bike rentals[cite: 2].
* **Main Predictors:** Temperature (`temp`) was identified as the strongest predictor of rental demand, followed by apparent temperature (`atemp`), humidity, and windspeed[cite: 2].
* **Seasonal Trends:** Average rental demand peaks during Summer and drops to its lowest during Spring[cite: 2]. Demand notably increases when temperatures reach a comfortable range of 22-26°C[cite: 2].

## Tech Stack
* Python (Pandas, Matplotlib, Scikit-learn)
