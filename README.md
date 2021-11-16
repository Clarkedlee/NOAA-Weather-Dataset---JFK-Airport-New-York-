# watson_studio_notbook

## Introduction
This notebook relates to the NOAA Weather Dataset - JFK Airport (New York). The dataset contains 114,546 hourly observations of 12 local climatological variables (such as temperature and wind speed) collected at JFK airport. This dataset can be obtained for free from the IBM Developer Data Asset Exchange.

In this notebook, we clean the raw dataset by:

- [x] removing redundant columns and preserving only key numeric columns
- [x] converting and cleaning data where required
- [x] creating a fixed time interval between observations (this aids with later time-series analysis)
- [x] filling missing values
- [x] encoding certain weather features

![JFK](https://github.com/Clarkedlee/watson_studio_notbook/blob/2d86a3e05691aa022eff4f8317346a611e62ce7f/JFK_airport.jpeg) 
