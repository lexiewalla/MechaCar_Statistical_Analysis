# MechaCar_Statistical_Analysis
module 15 Statistics and R


## Linear Regression to Predict MPG

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  The variables the provide a non-random amount of variance are the intercept, vehicle length and ground clearance. 

* Is the slope of the linear model considered to be zero? Why or why not?

  The slope of the linear model is not zero. Because the intercept, vehicle length and ground clearance are not of random variance. If all dependent values would have provided ranodm variance the slope would be zero.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  Our R-squared value is 0.71, this tells us that 71% of the time it will predict the mpg of the MechaCar effectively. There are most likely other variables other than the 6 we have already considered that would affect this value. 

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 3 is showing the most vairance of the 3. The all manufacturing lots came in around 62.3 and cannot exceed 100, lot 3 is at 170. This leaves Lot 1 and Lot 2 within the design specs. 


<img width="425" alt="deliv2" src="https://user-images.githubusercontent.com/45208773/144723667-2bdb978f-46b9-466d-bdff-e2392930f039.png">

<img width="425" alt="delv2" src="https://user-images.githubusercontent.com/45208773/144723652-a5aa5998-75d5-4151-9186-f3ef23d960ad.png">


## T-Tests on Suspension Coils

The p-values for both Lot 2 and lot 3 are both above the signifcance level showing that they are statistically similar to the mean.

<img width="491" alt="deliv3" src="https://user-images.githubusercontent.com/45208773/144723878-56d02b31-8ee7-4a05-b432-47135b793411.png">


## Study Design: MechaCar vs Competition

Another thing we can study is the safety of the MechaCar vs the competition cars. We can test the brake time and time it takes for airbags to deploy if the car were to get in an accident. We can make the null hypothesis that the MechCar is safer due to quicker brake times and air bag deploying. The alternative hypothesis will be the that the competition will be slower. We would have to measure the braking timing and air bag timing and then run a t-test to find the p-value and mean to determine the results. 


