# MechaCar Statistical Analysis
Project to review the MechaCar's production data for insights that may help the manufacturing team. Using R, design a linear model that predicts the mpg of MechaCar prototypes using several variables from the MechaCar_mpg.csv file

 ## Linear Regression to Predict MPG
 The lm() and summary(lm()) functions in R were used for this linearregression model to predict MPG based on vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD.
![image](https://raw.githubusercontent.com/kwarzeski/MechaCar_Statistical_Analysis/main/LinearRegressionPredictMPG.png)
- Vehicle length and ground clearance show significant impact on the mpg of the MechaCar. They show a non-random amount of variance (2.6x10-12 and 5.21x10-8)
- The p-value is 5.35e-11. Therefore the slope cannot be considered zero, as it is smaller than the significance level.
- The r-squared value is 0.7149, whichmeans this has an accuracy of 71.5%. This is a rough model and accuracy should be improved.
