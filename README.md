# US Housing Market & Macroeconomic Data Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on US macroeconomic indicators to understand their impact on the national housing market. Using Python, Pandas, and Matplotlib, the analysis cleans key economic variables and visualizes relationships across multiple dimensions.

## Key Features & Analysis Steps
* **Data Ingestion & Cleaning:** Loaded economic datasets, inspected schema metrics, and handled missing values.
* **Filtering & Feature Selection:** Filtered data based on unemployment thresholds and extracted relevant sub-dataframes.
* **Statistical Summary:** Evaluated distribution statistics for `Real_Disposable_Income` and `House_Price_Index`.
* **Data Visualization:**
  * **Scatter Plot:** Analyzed correlation between House Price Index and Real Disposable Income.
  * **Bar Chart:** Tracked Real GDP trajectory across time periods.
  * **Combo Chart:** Overlayed Consumer Price Index (bar) with Mortgage Rates (line) using dual Y-axes.
  * **Subplots:** Compare Stock Price Index and Consumer Price Index trends side-by-side.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib

## Dataset Attributes
* `Date`: Year of observation
* `House_Price_Index`: Housing price index base changes
* `Stock_Price_Index`: Stock market performance metrics
* `Consumer_Price_Index (CPI)`: Inflation measure via representative consumer basket
* `Unemployment_Rate`: Annual unemployment percentage
* `Real_GDP`: Inflation-adjusted gross domestic product
* `Mortgage_Rate`: Average interest rates on mortgages
* `Real_Disposable_Income`: Post-tax disposable income in billions

## How to Run
1. Clone this repository:
   ```bash
  git clone [https://github.com/hasnain-ch/us-housing-market-data-analysis.git](https://github.com/hasnain-ch/us-housing-market-data-analysis.git)
