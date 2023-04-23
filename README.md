# master-thesis-elena-yustres
**BEYOND THE ZONE: ASSESSING SPILLOVER EFFECTS OF MADRID CENTRAL ON AIR POLLUTION” (MASTER IN COMPUTATIONAL SOCIAL SCIENCE, 2022-2023)**

This repository contains the code and data used in my Master Thesis. Through an empirical analysis grounded in causal inference, I explore whether the implementation of the low emissions zone (LEZ) Madrid Central in 2018 led to pollution spillover effects in neighboring areas.

**Data Sources**

The following data sources were used in the analysis:

- Air quality data for the City of Madrid Air Quality Monitoring Network (csv) 

- Air quality data for the Community of Madrid Air Quality Monitoring Network, excluding the City of Madrid (csv)

- Data on control air quality stations in the City of Madrid (csv)

- Data on control air quality stations in the Community of Madrid of Madrid, excluding the City of Madrid (csv)

- Data on the LEZ perimeter (shp)

- Weather data for the Community of Madrid (AEMET API)

- Data on weather stations in the Community of Madrid, including the City of Madrid (AEMET API)

**Code**

The code for the analysis is written in R and is presented in an Rmd notebook which covers the following:

I. Data pre-processing and cleaning of air pollution, station location and weather data
II. Exploratory data analysis
III. Regression (Difference-in-Differences) analysis 
IV. Visualizations of the results


**Reproducing the Analysis**

To reproduce the analysis, clone the repository and run the Rmd. The necessary packages are listed in the beginnng of the file.

**Conclusion**

This repository contains the code and data used in the policy evaluation of Madrid Central in regards to its potential unintended effects beyond its perimeter. The analysis uses various data sources to explore the effects of the restrictions on neighboring areas. The code is organized into an Rmd file and can be run to reproduce the analysis.
