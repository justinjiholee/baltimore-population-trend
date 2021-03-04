# Baltimore Resident Population Trend
Research and analysis on the current trend for resident population in Baltimore City,MD

## Background
Baltimore City in Maryland currently has an estimated population of 600,000 people. The population in the United States has been gradually decreasing over the past few decades due to lower birth rates and new policies limiting immigration. I have decided to analyze to population trend in Baltimore to determine if the population in Baltimore has also been declining and predict the future population in the city based on the data sets. 

## Business Question
_As the resident population in Baltimore is declining every year, how would the population in Baltimore change in the near future?_

## Baltimore Population (1970-2019)
Extracting the public data sets from FRED Economic Research (https://fred.stlouisfed.org/series/MDBALT5POP), I was able to view and analyze the resident population in Baltimore from 1970-2019.
![alt text](https://github.com/justinjiholee/baltimore-population-trend/blob/main/Baltimore%20Population.png)

With the Excel data sets, I was able to create a cluster chart to see the relationship between the dates and population in Baltimore. Using simple linear regression, I produced the best fit line with an equation of y=-0.017x + 1304.3 and the R-squared value of 0.9414. This indicates that the population has a decreasing trend and it could explain 94% of the variance of Baltimore population. 
