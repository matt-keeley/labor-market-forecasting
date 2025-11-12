# U.S. Labor Market Forecasting

**Tech Stack:** R

## Project Overview
This project explores machine learning approaches to predict state-level unemployment rates in the U.S. by leveraging economic and housing data. The goal is to build predictive models that combine labor statistics with housing and mortgage data to better understand factors influencing unemployment trends.

## Data Sources
The analysis integrates three publicly available datasets:

1. **Bureau of Labor Statistics (BLS)** – Labor force and unemployment rates by state  
   - Source: [BLS Time Series Data](https://download.bls.gov/pub/time.series/la/)  
   - Files used: `la.measure`, `la.state_region_division`, `la.data.3.AllStatesS`

2. **National Mortgage Database (NMDB)** – New residential mortgage monthly statistics by state  
   - Source: [FHFA NMDB Data](https://www.fhfa.gov/data/national-mortgage-database-aggregate-statistics)

3. **Zillow Home Value Estimates** – State-level home value trends  
   - Source: [Zillow Research Data](https://www.zillow.com/research/data/)

## Methodology
1. **Data Cleaning & Integration**  
   - Combined BLS, NMDB, and Zillow datasets by state and month  
   - Handled missing values and standardized features for modeling  

2. **Feature Engineering**  
   - Created lagged variables to capture temporal trends  
   - Scaled numeric features for regression models  

3. **Modeling**  
   - Built predictive models to estimate state-level unemployment rates from economic and housing data  
   - Evaluated models using cross-validation to assess predictive performance  

4. **Visualization & Analysis**  
   - Visualized actual vs predicted unemployment rates  
   - Examined feature importance to identify key predictors  

## Output
- State-level unemployment predictions for upcoming months  
- Plots comparing predicted vs actual unemployment trends  
- Insights into how mortgage rates and housing values correlate with unemployment  
