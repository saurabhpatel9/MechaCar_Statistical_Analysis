# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
<li>Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

A variables with non-random amount of variance are Vehicle weight, spoiler_angle & AWD. Whereas this variables had the most amount of random variance: ground_clearance and vehicle_length.</li>

<li>Is the slope of the linear model considered to be zero? Why or why not?

The slope is not zero, we can say that by looking at the p-value, which is less than 0.05.</li>

<li>Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-squared value is 71%, which means approx ~71% of time the linear model will predict mpg values correctly. There might be other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.</li>

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
<li>Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 are both falling in design specifications and have almost the same exact mean and median. On the other hand Lot 3 has the most variance and exceeds the manufacturers specs.</li>

## T-Tests on Suspension Coils
Lot 1 and Lot 3 the PSI values are same as the population mean. However lot 2 the p-value is .347 which says there is evidence that the suspension coil is not same as the population mean. 
All t-tests are as below:

## Across all lots:
![r1](https://user-images.githubusercontent.com/86158802/136882262-91525509-b1e8-4b69-be1b-e16c0eb93291.PNG)

### Lot 1
![r2](https://user-images.githubusercontent.com/86158802/136882281-8405d1fe-d0c9-4165-8dc6-1161e621c9fe.PNG)

### Lot 2
![r3](https://user-images.githubusercontent.com/86158802/136882289-73c68640-bcce-4f44-8fb2-3fd8700f846a.PNG)

### Lot 3
![r4](https://user-images.githubusercontent.com/86158802/136882300-ae1c0e74-090e-4093-964b-11d7062f2063.PNG)

## Study Design: MechaCar vs Competition
How much hosepower does a car have is one of the factors buyers consider while buying car. This are primary factors consumer examine while buying Car:horsepower, mpg and size of engine. We can utilize our tests to see if MechaCar is much different from the competiton. Thus, a null hypothesis can be created stating that it is similar to the competition and the alternative would be the opposite of it.
In order to do this, we need to put in place a t-test after collecting the data from different types of competitor vehicles. Our t-test will help compare the population of all types of competitor vehicles.
