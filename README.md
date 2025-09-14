# Global Economic Insights: Unemployment and GDP Analysis with Machine Learning

## Project Overview
This project analyzes how global economic indicators influence unemployment trends across countries. It combines global unemployment data with GDP data from multiple years to explore relationships between GDP and unemployment rates. The project involves exploratory data analysis, feature engineering, and predictive modeling to uncover trends and economic insights.

## Dataset
The dataset combines:
- **Global unemployment data** by sex, age group, and age categories across countries.
- **GDP data** by country and year.  

**Scope:** Analysis is restricted to years **2020–2024**, where both GDP and unemployment values exist.

## Key Objectives
1. Explore the relationship between GDP and unemployment rates across countries.
2. Investigate trends in unemployment by age group and sex.
3. Identify unusual patterns or extreme values, such as high youth unemployment.
4. Build predictive models using polynomial features and Ridge regression to forecast unemployment rates.

## Data Cleaning and Preprocessing
- Missing values in numeric columns (GDP, Unemployment) were imputed using the **median** to reduce the effect of outliers.
- Country names were standardized to ensure consistency across datasets.
- Outliers were identified and capped at the 1st and 99th percentiles for modeling stability.
- Age group and category columns were standardized and trimmed for consistent text formatting.
- Numeric columns were scaled using **StandardScaler** for modeling purposes.
- Dataset filtered to include only years **2020–2024**.


## Future Work
- Incorporate additional economic indicators such as inflation, government spending, or labor participation rates.
- Build separate models for Youth and Adult unemployment to improve predictive accuracy.
- Visualize temporal and regional trends with interactive dashboards.

## License
© 2025 Ali Akcin. For educational purposes. All rights reserved.

