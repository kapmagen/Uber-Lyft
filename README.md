# Uber-Lyft
The project includes using Power Query and Python to process and clean data from the Uber &amp; Lift dataset, building relationships in the data model, using DAX to create calculated columns, and creating visualizations and dashboards in Power BI.

## Important: The data are synthesized and taken from kaggle. The purpose of the work is to show the ability to analyze.

## Probable insights based on the column names:
+ Price variability based on cab type and surge multiplier
+ Correlation between distance and price
+ The impact of weather on ride demand

### Price variability based on cab type and surge multiplier
[![PBIDesktop-r-NGm-Qq-CAC6.png](https://i.postimg.cc/jdqhQGGW/PBIDesktop-r-NGm-Qq-CAC6.png)](https://postimg.cc/fkFXMgWZ)
[![PBIDesktop-XGMDxtm7-Io.png](https://i.postimg.cc/xC4tXg1x/PBIDesktop-XGMDxtm7-Io.png)](https://postimg.cc/KktnVPLB)

##### These charts clearly show both market strategy and market volumes. Also it allow quickly compare Uber and Lyft prices and see how much the price increase multiplier affects the cost of a trip. 



### Correlation between distance and price and the impact of weather on ride demand

[![PBIDesktop-9-WUN85-YDm-A.png](https://i.postimg.cc/T3HMXzzF/PBIDesktop-9-WUN85-YDm-A.png)](https://postimg.cc/757Q3WYn)
##### In this graph we see a slight linear relationship, so the next step is to use a python script to find correlations in the dataset
[![PBIDesktop-z1q-Ezscqzm.png](https://i.postimg.cc/7b8hXCV1/PBIDesktop-z1q-Ezscqzm.png)](https://postimg.cc/FkphHHw1)
##### 
