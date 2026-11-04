# Bike Rental Demand Analysis and Prediction

## About the Project
This project explores daily bike rental demand for the Rockhampton Regional Council using exploratory data analysis (EDA) and predictive modelling.

The aim was to identify how seasonal and weather conditions influence bike usage and to evaluate whether historical data could be used to forecast future rental demand.

## Tech Stack
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Demand Over Time

![Bike Rental Demand Over Time](images/Bike%20Rental%20Demand%20Over%20Time.png)

Bike rental demand changes considerably throughout the year, with the 30-day rolling average showing clear seasonal patterns.

## Seasonal Patterns

![Average Bike Rentals by Season](images/Average%20Rentals%20by%20Season.png)

Summer recorded the highest average rental demand, while Spring had the lowest.

## Temperature and Rental Demand

![Temperature vs Rentals by Season](images/Temperature%20vs%20Rentals%20by%20Season.png)

Rental demand generally increased with temperature, with particularly strong demand around 22–26°C.

## Weather Conditions

![Bike Rental Distribution by Weather Condition](images/Bike%20Rental%20Distribution%20by%20Weather%20Condition.png)

Clear conditions were generally associated with higher rental demand, while storm conditions showed lower usage.

## Predictive Modelling

Two models were compared:

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| Linear Regression | 229.47 | 185.09 | 0.473 |
| Random Forest | **113.60** | **87.57** | **0.871** |

Random Forest substantially outperformed Linear Regression, explaining approximately 87% of the variance in daily bike rental demand.

## Feature Importance

![Random Forest Feature Importance](images/Feature%20importance%20plot.png)

Temperature (`temp`) was by far the strongest predictor, followed by apparent temperature (`atemp`), humidity and windspeed.

## Key Findings
- Random Forest was the best-performing model with an R² of **0.871**.
- Temperature was the strongest predictor of rental demand.
- Summer had the highest average rental demand.
- Demand was strongest around **22–26°C**.
- Clear weather was generally associated with higher demand than storm conditions.

## Repository Structure
- `Code_by_Kseniia_Zaichenko_12264917.ipynb` — data cleaning, EDA and predictive modelling
- `bike_rental.csv` — bike rental dataset
- `12264917-report.pdf` — full analysis report
- `images/` — visualisations used in this README
