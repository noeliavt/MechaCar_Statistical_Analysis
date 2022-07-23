# MechaCar_Statistical_Analysis

## 1. Linear Regression to Predict MPG


<p align="center">
  <img  src="Resources/LinearRegresion1.png">
</p>

* In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results vehicle length and ground clearance (and Intercept) provide a non-random amount of variance to the linear model of mpg.

According to the results, the multi linear model is:

`hsl(mpg = 6.27 * vehicle_length + 1.25e-3 * vehicle_weigth + 6.88e-2 * spoiler_angle -3.41 * AWD + 3.55 * ground_clearance - 1.04e+2)`

`hsl(mpg = 6.27 * vehicle_length - 3.41 * AWD + 3.55 * ground_clearance - 104)'

* Then the slope of the linear model is not considered to be zero.

* R-square is 0.71 so 71% of the variations in mpg can be explained by changes in the vehicle length, the vehicle weight, the spoiler angle, the drivetrain and the ground clearance. We can consider this linear model as efficient to predict mpg of MechaCar prototypes.

## 2. Summary Statistics on Suspension Coils
