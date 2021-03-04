# Baltimore Resident Population Trend
Research and analysis on the current trend for resident population in Baltimore City,MD

## Background
Baltimore City in Maryland currently has an estimated population of 600,000 people. The population in Baltimore has been gradually decreasing over the past few decades as the population was about 800,000 in the 1970s. There could be various factors for this decline in population such as lower birth rates, but as Baltimore is ranked 4th in the most dangerous cities in the United States by CBS, I wanted to see if the number of homicides contributed to this. I have decided to analyze the population trend in Baltimore and predict the future population in the city based on the data sets. Also, I will determine if the the number of homicides has any relationship with the population. 

## Business Question
_What is the current trend for resident population in Baltimore and what would be an estimated population in the city in the near future? Does number of homicides influcence the population trend?_

## Baltimore Population (1970-2019)
Extracting the public data sets from FRED Economic Research (https://fred.stlouisfed.org/series/MDBALT5POP), I was able to view and analyze the resident population in Baltimore from 1970-2019.
![alt text](https://github.com/justinjiholee/baltimore-population-trend/blob/main/Baltimore%20Population.png)

With the Excel data sets, I was able to create a cluster chart to see the relationship between the number of years passed since 1970 and population in Baltimore. 
![alt text](

Using simple linear regression, I produced the best fit line with an equation of y=-4.4266x + 836.31 and the R-squared value of 0.6021. This indicates that the population has a decreasing trend and it could explain 60% of the variance of Baltimore population. The standard error of residuals is 59.424, meaning that about 59,424 people above or below the best fit line is within 68% of the data.
