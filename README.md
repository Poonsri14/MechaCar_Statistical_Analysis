# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG
![1](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/MechaCarSum.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

    Vehicel length and ground clearance will provide a non random amounth of varance because has a small p-value.
    Vehicel weight, spoilter angle, and AWD will provide a random amounth of varance because has a large p-value.

Is the slope of the linear model considered to be zero? Why or why not? 
      
    No, because of the p-value is smaller than 0.05.


Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
      
    The modle will predict at a 71.49% accuracy.


## Summary Statistics on Suspension Coils

#### Total Sammary
![2](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/TotalSum.png)

#### Lots Summary
![3](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/LotSum.png)


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils 
must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification 
for all manufacturing lots in total and each lot individually? Why or why not?

     The entire manufacturing lots meet the design specicafication bacause the variance is 62.29 PSI.
     which is within the 100 PSI requirement.Lot 1 and lot 2 are passed, but lot 3 doesn't as it's showing on the images above.


## T-Tests on Suspension Coils

#### T-Test for All Lots

![4](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/t-testAllLot.png)

#### T-Test for Lot 1

![5](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/t-testLot1.png)


#### T-Test for Lot 2

![6](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/t-testLot2.png)


#### T-Test for Lot 3

![7](https://github.com/Poonsri14/MechaCar_Statistical_Analysis/blob/main/images/t-testLot3.png)

    According to the images for T-Tests on suspension coiles per each lot, lot 1 has the hightest P-value, 
    then lot 2, and lot 3, respectively.


## Study Design: MechaCar vs Competition

What metric or metrics are you going to test?

    I'm going to test on Cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.


What is the null hypothesis or alternative hypothesis?

    Null Hypothesis: MechaCars have no difference in pricing compared to its competitors based on its perforamce of key factors.

    Alternative Hypothesis: MechaCars have different pricing in comparison to competitors based onn its performance of key factors.


What statistical test would you use to test the hypothesis? And why?

    Mutiple linear regresstion to compare differce factors to the selling price.


What data is needed to run the statistical test?

    There would be data on cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

