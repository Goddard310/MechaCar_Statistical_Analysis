# MechaCar_Statistical_Analysis

## Overview

We're charged with analyzing MechaCar's production to help the manufacturing team. In order to conduct this analysis, we are using two datsets containing information related to the miles per gallon and the suspension coils of the MechaCar.

## Linear Regression - MPG
1.  There were two variables that provided a non-random amount of variance: Both of the "length" and "ground clearance" have extremely small p-value meaning that they had a high level of significance. It also should be noted that the intercept had a high level of significance meaning that there are still other factors contributing to the variance of the MPG.
2.  The slope of the linear model is not considered to be zero -- the linear regression shows that some of the independent variables had an effect on the dependent variable. 
3.  The r-squared value is at 0.7149 mean.  This means that the model would be considered moderately effective.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/MPG%20p_value.png)

## T-test - Suspension Coils

Using a significance level of 95%: 
After running the tests, all four p-values where much greater than .05 meaning that I would fail to reject that there is a statistical difference between the four groups and the population mean.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/PSI%20t_test.png) 


### Lot Test
![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/multi-lot%20t_test.png)


## Summary

1.  **Null Hypothesis:** All of the cars in the same class have the same fuel efficieny. **Alternative Hypothesis:** The cars do not have the same fuel efficiency.
2.  We could use an ANOVA test to complete this analysis for both types of fuel efficiencies and use the ggplot2 library to show the potential spread between different cars using a boxplot.
3.  We would need the fuel efficiency data from 50 individual cars to create a sample size of data for each car in the class type. For example, if there were 10 cars in the class type, we would have 500 data points collected for each type.

