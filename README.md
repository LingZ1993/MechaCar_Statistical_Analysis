# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG

<img src="screenshot/Deliverable 1- Linear Regression.png">

Answering following questions: 
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 - vehicle weight(0.0776)
 - spoiler angle(0.3069)
 - AWD(0.1852)
2. Is the slope of the linear model considered to be zero? Why or why not?
 - The slope of the linear model is not considered to be zero because the p-value is less than 0.05.
3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 - The r-squared value is 0.71, which means that approximatley 71% of all mpg predictions are correct. Also P-Value is smaller than siginificance value (94.65% < 95%). 

## Summary Statistics on Suspension Coils

<img src="screenshot/Deliverable 2- Suspension.png">

<img src="screenshot/Deliverable 2- Lot 1.png">
<img src="screenshot/Deliverable 2- Lot 2.png">
<img src="screenshot/Deliverable 2- Lot 3.png">

Address the following question: 
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 - Lot 1 and Lot 2 meets the design specification, while Lot 3 does not meet the specification, because the variance exceeded 100 pounds per square inch (170.2861224). 
