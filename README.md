# Baltimore Resident Population Trend
Research and analysis on the current trend for resident population in Baltimore City,MD

## Background
Baltimore City in Maryland currently has an estimated population of 600,000 people. The population in Baltimore has been gradually decreasing over the past few decades as the population was about 800,000 in the 1970s. There could be various factors for this decline in population such as lower birth rates, but as Baltimore is ranked 4th in the most dangerous cities in the United States by CBS, I wanted to see if the number of homicides contributed to this. I have decided to analyze the population trend in Baltimore and predict the future population in the city based on the data sets. Also, I will determine if the the number of homicides has any relationship with the population. 

## Business Question
_What is the current trend for resident population in Baltimore and what would be an estimated population in the city in the near future? Does number of homicides influcence the population trend?_

## Baltimore Population (1970-2019)
Extracting the public data sets from FRED Economic Research (https://fred.stlouisfed.org/series/MDBALT5POP), I was able to view and analyze the resident population in Baltimore from 1970-2019.
![alt text](https://github.com/justinjiholee/baltimore-population-trend/blob/main/Baltimore%20Population.png)
## Baltimore Population Trend and Prediction
With the Excel data sets, I was able to create a cluster chart to see the relationship between the number of years passed since 1970 and population in Baltimore. 
![alt text](https://github.com/justinjiholee/baltimore-population-trend/blob/main/Baltimore%20Population%20Trend%20Graph.png)

Using simple linear regression, I produced the best fit line with an equation of y=-6.206x + 869.9 and the R-squared value of 0.9414. This indicates that the population has a decreasing trend and it could explain 94% of the variance of Baltimore population. The standard error of residuals is 22.814, meaning that about 22,814 people above or below the best fit line is within 68% of the data.

With this data, I was able to predict the population in Baltimore for 2025, 2030, and 2040.

2025: 528,570

2030: 497,540

2040: 435,480

## Baltimore Population and Number of Homicides
![alt text](https://github.com/justinjiholee/baltimore-population-trend/blob/main/Data%20Analysis.png)
Using multiple linear regression methods through excel, I wanted to see if the population is affected by the number of homicides. 
The coefficient from the data suggests that the Predicted Population = 808.314 -0.0254 (Number of Homicides) -5.274(Number of years passed). As the value of Significance F is very low, it suggests that the both variables of number of homicides and number of years passed are significant to the result. However, as the P-Value for number of homicides is 0.62, it is insignificant to conclude that the number of homicides affect the population in Baltimore.

## Conclusion
As a college student in Baltimore, I wanted to learn and analyze the trend of resident population in the city. I have found out that the population is actually declining over the years and it will continue to decrease. As I wanted to find out the reason for this decline, I thought that the number of homicides could be an essential factor. Using multiple linear regression analysis, I concluded that the evidence is insignificant to consider the number of homicides as a decrease in population. In a future research, I hope to utilize other factors that could possibly lead to the population decline in Baltimore


