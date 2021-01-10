# Improvement
don't have household information on household level, only have that on acorn group level.
out-dated

# 2020.10.05
* Meet with mentors
* Try regression models, all very bad: 0.04-0.06 accuracy
	- w/ grouping
	- w/o grouping
	- PCA top 3 components

# 2020.10.04
* Data cleaning
	- drop outliers
	- start from 2012.01.23
	- drop household have less than 48 records and 100 days
	- merge with `Acorn_cleaned_percentage.csv`, `Acorn_cleaned_boolean.csv` (only two columns), and `informations_households.csv`
* Clearn `acorn_details.csv`
	- convert index values to percentage (across Acorn groups)
	- create both percentage and boolean `attitude` and `environment_group`, saved as `Acorn_cleaned_boolean.csv` and `Acorn_cleaned_percentage.csv`
* Create EDA for geographical and financial features
	- bar plots
	- line plots (codes from Nandhitha, wrap it in a function)
* Try PCA: 3 main components

# 2020.09.29
* Clearn `acorn_details.csv`
	- hard-code to regroup features, then 
		- groupby new features and sum
		- convert index values to boolean






