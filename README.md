# MechaCar Statistical Analysis
Project to review the MechaCar's production data for insights that may help the manufacturing team. Using R, design a linear model that predicts the mpg of MechaCar prototypes using several variables from the MechaCar_mpg.csv file

 ## Linear Regression to Predict MPG
 The lm() and summary(lm()) functions in R were used for this linearregression model to predict MPG based on vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD.
![image](https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/images/LinearRegressionPredictMPG.png)
- Vehicle length and ground clearance show significant impact on the mpg of the MechaCar. They show a non-random amount of variance (2.6x10-12 and 5.21x10-8)
- The p-value is 5.35e-11. Therefore the slope cannot be considered zero, as it is smaller than the significance level.
- The r-squared value is 0.7149, whichmeans this has an accuracy of 71.5%. This is a rough model and accuracy should be improved.

## Summary Statistics on Suspension Coils
The mean and median for suspension coil PSI is almost 1500 for all lots (1498.78 and 1500 respectively) with a variance of 62.29 and standard deviation of 7.89. Looking at the Lot Summary, Lots 1 and 2 have an even lower standard deviation and variance, while Lot 3 has the highest, with a variance of 170.29 and standard deviation of 13.04.
### Total Summary
![https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/images/suspension_totalSummary.png](https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/images/suspension_totalSummary.png)
### Lot Summary
![https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/images/suspension_lotSummary.png](https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/images/suspension_lotSummary.png)
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 
- The current data shows that the manufacturing data meets this specification for all lots in total, but Lot 3 does not meet this specification individually. Lots 1 and 2 have low enough variance to cover Lot 3's variance.
