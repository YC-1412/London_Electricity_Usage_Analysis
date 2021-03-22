# London_Electricity_Usage_Analysis
To better understand the electricity consumption and upgrade the energy supply to tackle climate change, the British government installed smart meters in every home in England, Wales, and Scotland. Based on the data from these meters, our project aims to identify the patterns and predict energy consumption, and then provide some suggestions on energy-saving strategies.

This is the Capstone project of the Correlation One Women's Summit. Our team analyzed the factors that influence the energy consumption by exploratory analysis, and predicted average daily energy consumption for different demographic groups using ARIMA model.

## Data
Smart meter data from London area: https://www.kaggle.com/jeanmidev/smart-meters-in-london

## Sitemap
`Data_preprocessing`: All the data pre=processing scripts
	`Acorn_cleaning.ipynb`: Demographic data cleaning
	`preprocessing.ipynb`: Time data cleaning
	`energy_cleaning.ipynb`: Electricity data cleaning
`EDA`
	`EDA-Nandhitha.ipynb`: Initial look at the data and the relation between electricity usage and potential influential factors
	`EDA_acorn_ratio_regression.ipynb`: EDA with demographic factors (ethnicity) and tentative regression analysis
	`EDA_economic.ipynb`: EDA with economic factors
	`household.ipynb`: EDA with demographic factors (age, ethnicity, house size, child)
`Time_series_analysis`
	`DS4A_time_series.ipynb`: Time series analysis of average daily energy consumption using ARIMA

## Team member
Nandhitha Raghuram, Yingyu Cao, Priyanka Lahoti, Sonali Medani, Tanvi Pareek