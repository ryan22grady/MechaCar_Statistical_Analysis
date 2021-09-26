# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

-Is the slope of the linear model considered to be zero? Why or why not?

Our slope is not zero just be looking at the p-value, which is less than 0.05.

-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Our R-squared value is 71%, which means roughly ~71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.

## Summary Statistics on Suspension Coils

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 are both within design specifications and have hnearly the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

## T-Tests on Suspension Coils

- Lot 1 and Lot 3 the PSI values are not different from the population mean. However lot 2 the p-value is .347 which means there is evidence that the suspension coil is different from the population mean. All t-tests can be seen below:

### Across all lots:

![Screen Shot 2021-09-26 at 4 59 05 PM](https://user-images.githubusercontent.com/84995704/134825611-09d6606d-a2d7-4795-9dc5-24230705135d.png)

![Screen Shot 2021-09-26 at 4 58 23 PM](https://user-images.githubusercontent.com/84995704/134825612-69461ab5-db6a-4648-afee-a0b60cc0e18c.png)

![Screen Shot 2021-09-26 at 4 57 55 PM](https://user-images.githubusercontent.com/84995704/134825615-8bd4cdc4-4753-4bdd-a9ae-e44758611662.png)

![Screen Shot 2021-09-26 at 4 57 24 PM](https://user-images.githubusercontent.com/84995704/134825616-7d21b74b-ff39-4351-a84a-7ac63a2f5705.png)

## Study Design: MechaCar vs Competition

- One feature that people are interested in when buying a car is how much horsepower the car has. I think horsepower, mpg and how large the engine is are 3 factors that go into consumer decision making. We can use our tests to see if our MechaCar is much different from the competiton. We can make a null hypothesis stating that it is not different from the competition and our Alternative would be the opposite. To do this we will need to use our t-test after collecting data from different types of competitor vehicles. Our t-test will be comparing the population of all types of competitor vehicles.
