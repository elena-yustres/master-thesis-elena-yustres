# master-thesis-elena-yustres
**BEYOND THE ZONE: ASSESSING SPILLOVER EFFECTS OF MADRID CENTRAL ON AIR POLLUTION” (MASTER IN COMPUTATIONAL SOCIAL SCIENCE, 2022-2023)**

This repository contains the code and data used in my Master Thesis. Through an empirical analysis grounded in causal inference, I explore whether the implementation of the low emission zone (LEZ) Madrid Central at the end of 2018 led to spillover effects in the pollution levels in neighboring areas.

**Data Sources**

The following data sources were used in the analysis:

- Air quality data for the Air Quality Monitoring Network of the City of Madrid with *hourly* frequency (csv) 

- Air quality data for the Air Quality Monitoring Network of the Community of Madrid, excluding the City of Madrid with *hourly* frequency (csv)

- Data on air quality monitoring stations in the City of Madrid (csv)

- Data on air quality monitoring stations in the Community of Madrid of Madrid, excluding the City of Madrid (csv)

- Data on the LEZ perimeter (shp)

- Data on the Madrid administrative boundaries (GeoJSON)

- Weather data for the Community of Madrid with *daily* frequency (AEMET API)

- Data on weather stations in the Community of Madrid, including the City of Madrid (AEMET API)

- Noise pollution data for the Monitoring Network of the City of Madrid with *monthly* frequency (csv) 

- Data on noise quality monitoring stations in the City of Madrid (csv)

**Code**

The code for the analysis is written in R and is presented in an Rmd notebook which covers the following:

I. Pre-processing of air pollution and station location data

II. Exploratory data analysis

III. Pre-processing, imputation and descriptive analysis of weather data 

IV. Difference-in-Differences Regression: results and analysis 

V. Robustness checks

VI. Additional resources: identification streategy and auxiliary figures in the main document


**Reproducing the Analysis**

To reproduce the analysis, clone the repository and run the Rmd. The necessary packages are listed in the beginnng of the file.

**Conclusion**

This repository contains the code and data used in the policy evaluation of Madrid Central in regards to its potential unintended effects beyond its perimeter. The analysis uses various data sources to explore the effects of the restrictions on neighboring areas. The code is organized into an Rmd file and can be run to reproduce the analysis.
