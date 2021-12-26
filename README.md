# MechaCar_Statistical_Analysis

## Overview

We're charged with analyzing MechaCar's production to help the manufacturing team. In order to conduct this analysis, we are using two datsets containing information related to the miles per gallon and the suspension coils of the MechaCar.

## Linear Regression - MPG
1.  There were two variables that provided a non-random amount of variance: The vehicle length and the ground_clearance. Both of these have extremely small p-value meaning that they had a high level of significance. It also should be noted that the intercept as had a high level of significance meaning that there are still other factors contributing to the variance of the miles per gallon of the MechaCar.
2.  The slope of the linear model is not considered to be zero. This is because the linear regression shows that some of the independent variables had a significant effect on the dependent variable. If none of the independent variables had an effect on the dependent variable then the linear regression would result in a near zero slope.
3.  The main indicator of whether the linear model predicts the mpg of the MechaCar is the r-squared value. In this case, it is at 0.7149 mean that out of 100 instances, this model would approximately predict the mpg of the MechaCar correctly 71 times. This means that the model would be considered effective.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/MPG%20p_value.png)

## Summary Stats - Suspension Coils

Looking at the total summary, the current variance is approximately 76.23 PSI meaning that is does meet the design specification. When looking at the lots individuals, the first two lotas meet the design specification at a varaince of approximately 1.14 PSI and 10.13 PSI respectfully, but the third lot does not. This is becasue the third lot's variance is approximately 220.01 PSI, exceeding the design specification by more than double the alotted amount. Therefore, the manufacturing team should work with the cars in lots 1 and 2 compared to those in lot 3.

![Alt text](https://github.com/Goddard310/MechaCar_Statistical_Analysis/blob/main/images/PSI%20t_test.png) 


## Lot Test


## Conclusion 


