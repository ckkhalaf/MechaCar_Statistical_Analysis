# MechaCar_Statistical_Analysis
Data Bootcamp Week 16- R

## Overview of Analysis
The purpose of this analysis is to help a data analytics team do the following: 

-Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
-Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
-Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
-Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG

![Image of Linear Regression](resources/linear_reg.png)

The above linear regression model depicts our response variable is mpg and our predictable variables are vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD. Based on the data, the vehicle length and ground clearance are the main variables contributing to the prototype's mpg performance. The slope of the linear model is not zero because the p-value of 5.35e-11. The r-squared and p-value determines that this model does predict the mpg of MechaCar prototypes effectively.


## Summary Statistics on Suspension Coils

![Image of Total Summary](resources/total_summary.png)

![Image of Lot Summary](resources/lot_summary.png)


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data does meet this design specification for all manufacturing lots in total and each lot individually with the exception of Lot 3 where it exceeds the threshold. 

## T-Tests on Suspension Coils

![Image of All T-Tests](resources/ttest_all_lots.png)

![Image of T-Test 1](resources/ttest_lot1.png)

![Image of T-Test 2](resources/ttest_lot2.png)

![Image of T-Test 3](resources/ttest_lot3.png)

then briefly summarize your interpretation and findings for the t-test results.

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
What metric or metrics are you going to test?

What is the null hypothesis or alternative hypothesis?

What statistical test would you use to test the hypothesis? And why?

What data is needed to run the statistical test?
