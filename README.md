# MechaCar_Statistical_Analysis

## Overview
AutosRUS is reviewing statistical data points of the manufacturing process to find opportunities for higher consistency. Analysts have been tasked to review data points gathered from prototype vehicles to determine predictable MPG. We also need to provide summary statistics for suspension coil manufacturing in whole and by individual manufacturing locations. Then propose a study to futher compare MechaCar against competitive manufacturers.

## Linear Regression to Predict 

MPG<img width="511" alt="Screen Shot 2022-09-10 at 3 05 35 PM" src="https://user-images.githubusercontent.com/106006911/189503153-5679e232-06de-42d5-b9ae-069f16d6f093.png">

* This multi-linear regression is run on 6 data points. It shows that vehicle length and ground clearance have the most significant effect on MPG. Vehicle weight has a minor effect, as well. The slope is not zero, and the p-values are low, so we must reject the null-hypthesis. The relattionships between the variables and MPG is more than chance. With a r-squared result of better than 71%, this model will provide accurate predictions.

## Summary Statistics on Suspension Coils

<img width="330" alt="Screen Shot 2022-09-10 at 3 54 30 PM" src="https://user-images.githubusercontent.com/106006911/189503214-326d94d8-f9b8-4c96-a12e-5e8f83daed3a.png">

* When reviewed as a whole, variance is within 100 psi, as set by company policy.

<img width="493" alt="Screen Shot 2022-09-10 at 4 09 24 PM" src="https://user-images.githubusercontent.com/106006911/189503262-b0d60107-56c2-4cfe-b41a-bd1036276327.png">

* When reviewed by individual lots, lots one and two are well within the acceptable variance. Lot 3 is well out of range with a variance of 170+; thus the single greatest contributor to negative drag on overall performance. It would be important for lots 2 and 3 to confir with lot 1 to decrease the variance in their suspension coils.
 
## T-Tests on Suspension Coils

<img width="404" alt="Screen Shot 2022-09-10 at 5 06 27 PM" src="https://user-images.githubusercontent.com/106006911/189503329-3203f163-d1b2-428c-a268-cd1c76de1f46.png">

* Overall T-test results for the suspension coils across all manufacturing plants show they are not statistically different from the population mean, and the p-value is not low enough to reject the null hypothesis.

<img width="487" alt="Screen Shot 2022-09-10 at 4 29 19 PM" src="https://user-images.githubusercontent.com/106006911/189503345-b83679f2-9cb1-4d88-b9a0-40826d52f29f.png">

* Lot 1 has performed strongest of the three locations. With a p-value of one, we cannot reject the null hypothesis.

<img width="482" alt="Screen Shot 2022-09-10 at 4 30 37 PM" src="https://user-images.githubusercontent.com/106006911/189503367-3eb2bb29-1968-4854-86a8-2b5c85476f32.png">

* Lot 2 has preformed well and the p-value is not low enough to reject the null hypothesis.

<img width="481" alt="Screen Shot 2022-09-10 at 4 33 05 PM" src="https://user-images.githubusercontent.com/106006911/189503377-f7546c03-1fc2-4df4-bd79-74e676d9d42e.png">

* Lot 3 has not met company standard tolerance in manufacturing this part. The p-value is below .05, so we must reject the null hypothesis.

## Study Design: MechaCar vs Competition

A metric that people are interested in when it comes to vehicles is safety ratings. We would need to collect safety rating data for a large number of comparable vehicles. Create a study that tests whether or not MechaCar is statistically different from a collection of comparable vehicals. The null hypothesis would be that there is no statistical differece between MechCar and comparable vehicles. The alternative hypothesis is that there is a statistical difference. The statistical test we can use is a one sample t-test where the population data will be all comparable vehicles. We will need multiple data points that affect the saftey rating on comparable vehicles, as well as for MechaCar.
