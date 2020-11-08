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
 
 ## T-Tests on Suspension Coils 

<img src="screenshot/Deliverable 3- All Lots.png">
<img src="screenshot/Deliverable 3- Lot 1.png">
<img src="screenshot/Deliverable 3- Lot 2.png">
<img src="screenshot/Deliverable 3- Lot 3.png">

Above we have Screenshots of the t-test for all lots and then break down into each individual lot; According to the result for all lots, the p-value is showing 0.06028, and it is outside the significance level of 0.05, therefore, it there is no sufficient evidence to reject the null hypothesis. 

## Study Design: MechaCar vs Competitions

When purchasing, I think most of the consumers are looking for a more fuel efficient car, so in order to out-duel their competitions, improving their fuel efficiency would be the best choice. Therefore I choose the fuel efficiency. 
To determine the MPG numbers, we need to gather data from MechaCar and also their competitions as well, several outside factors such as city or highway, the length of the trips and also temperature could be a factor as well. 

Addressing the following questions: 

1. What metric or metrics are you going to test?
 - We need large sample of dataset
 - Dataset needs to be randomly selected
 
2. What is the null hypothesis or alternative hypothesis?
 - Null Hypothesis: There is no statistically difference between the MPG numbers of MechaCar and their competitions' MPG numbers;
 - Alternative Hypothesis: The mean of the MPG numbers of MechaCar is greater than their comptitions. 
 
3. What statistical test would you use to test the hypothesis? And why?
 - t-test would be optimal to use to test the hypothesis, it'd be better to use the test that is currently in use in this analysis. 
 
4. What data is needed to run the statistical test?
 - We need to get MPG numbers for MechaCars and also their competitions, in order to perform the t-test to get the p-value, if we get a p-value number that is less than 0.05 then we can reject the null. 
