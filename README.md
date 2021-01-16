# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
### The independent variables of vehicle length and ground clearance contributed a non-random amount of varience to the mpg values in the dataset because of the small Pr(>|t|) values. With a p-value of 5.35e-11, we can reject the null-hypothesis and state that there is a significant linear relationship and the slope of the linear model is not zero. An r-squared value of 0.72 indicates that this model is moderately sufficient to predict future observations. 
## Summary Statistics on Suspension Coils
### The manufacturing data does meet the design specification of not exceeding 100 PSI for the manufacturing lots in total because the varience plus standard deviation is less than 100. However, lot 3 does not meet the design specification on it's own by the same logic while lot 1 and 2 do meet the specification. 
## T-Tests on Suspension Coils
### For lots 1 and 2, the PSI values and mean is statistaically significant because the p-value is 1 and 0.6 respectively. Assuming a 0.05 significance level, lot 3 is significantly different from the mean. The p-value for lot 3 is 0.041. 
## Study Desgin: MechaCar vs Competition
### We are going to design a study that attempts to find the optimal range of car prices that maximize fuel efficiency, safety rating, and maintenance cost. The null hypothesis is that there is no statistical difference between price and these three independent metrics. The alternative hypothesis is that there is a statistical difference between price and these three metrics. We are going to run a mulitiple linear regression test. We must ensure that our safety rating data is in a continuous form, and that our maintencance cost is inverted. 
