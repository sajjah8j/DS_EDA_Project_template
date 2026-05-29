# King County Housing Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) of residential properties in King County, Washington. The objective is to understand the key factors influencing house prices and provide data-driven recommendations for a specific client.

## Business Problem

The client, Nicole Johnson, is looking to purchase a house in a lively and relatively central neighborhood while staying within a moderate budget.

## Dataset

The dataset contains housing sales data from King County, Washington and includes price, bedrooms, bathrooms, living area, lot size, waterfront access, view rating, condition, grade, renovation data, zipcode, coordinates, and sales date.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- SQLAlchemy
- PostgreSQL

## Key Insights

1. Living area is one of the strongest drivers of house prices.
2. Housing prices vary significantly across zipcodes.
3. Waterfront properties command premium prices.
4. Luxury homes create strong right-skewness in the price distribution.

## Recommendations

1. Focus on moderately priced central-adjacent neighborhoods.
2. Prioritize living space over bedroom count.
3. Monitor seasonal market timing.
4. Consider renovated homes in mid-priced areas.

## Repository Structure

```text
├── EDA_sajjad.ipynb
├── README.md
├── requirements.txt
└── data/
```

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open EDA_sajjad.ipynb and run all cells.
