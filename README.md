# MechaCar_Statistical_Analysis

## Overview

We're charged with analyzing MechaCar's production to help the manufacturing team. In order to conduct this analysis, we are using two datsets containing information related to the miles per gallon and the suspension coils of the MechaCar.

## Linear Regression - MPG
1.  There were two variables that provided a non-random amount of variance: The vehicle length and the ground_clearance. Both of these have extremely small p-value meaning that they had a high level of significance. It also should be noted that the intercept as had a high level of significance meaning that there are still other factors contributing to the variance of the miles per gallon of the MechaCar.
2.  The slope of the linear model is not considered to be zero. This is because the linear regression shows that some of the independent variables had a significant effect on the dependent variable. If none of the independent variables had an effect on the dependent variable then the linear regression would result in a near zero slope.
3.  The main indicator of whether the linear model predicts the mpg of the MechaCar is the r-squared value. In this case, it is at 0.7149 mean that out of 100 instances, this model would approximately predict the mpg of the MechaCar correctly 71 times. This means that the model would be considered effective.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/MPG%20p_value.png)

## T-test - Suspension Coils

By using a significance level of 95%, meaning that 95% of the time this tests results would be true, I tested to see if any of the four groups had a statistical difference from the mean of 1,500 PSI. After running the tests, all four p-values where much greater than .05 meaning that I would fail to reject that there is a statistical difference between the four groups and the population mean.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/PSI%20t_test.png) 


#### Lot Test
![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/multi-lot%20t_test.png)


## Summary

1.  Null Hypothesis is that all of the cars in the same class have the same fuel efficienies. THe Alternative Hypothesis is that they are not all the same.
2.  I would use an ANOVA test to complete this analysis for both types of fuel efficiencies. Also I would use the ggplot2 library to show the potential spread between different cars using a boxplot.
3.  I would need fuel efficiency data from 50 individual cars to create a sample size of data for each car in the class type. For example, if there was 10 cars in the class type, I would have a top of 500 data points collected for each fuel efficiency type.

