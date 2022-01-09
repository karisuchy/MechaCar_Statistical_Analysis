# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

As demonstrated by the linear regression summary below:

- Vehicle length and ground clearance both provide statistically significant impact on mpg. This is clear because the p-value for each is less than .05. 
- The slope of the linear model is not considered zero. A slope in any one variable means there will be a slope in the overall linear mode. The chart shows multiple slopes as demonstrated by the estimate column.
- The Multiple R-Square of 0.6825 effectively demonstrates that this linear model does effectively predict the mpg of MechaCar prototypes.


![MPG Linear Regression](https://user-images.githubusercontent.com/90162669/148667612-8c9819a4-f89f-41f9-8ddf-2bec41506d39.png)


## Summary Statistics on Suspension

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

- Overall: As shown below, the variance of 62.3 demonstrates the combined manufacturing lots do meet this required design specification. 

![total_summary_table](https://user-images.githubusercontent.com/90162669/148667959-500d5a34-4c95-446e-a650-f570fa411897.png)

- Individual lots: As shown below, Lots 1 and 2 also meet the design specifications for variance at .98 and 7.47 respectively.  However, Lot 3 is not meeting this specification as demonstrated by the variance of 170.24.  

![lots_summary_table](https://user-images.githubusercontent.com/90162669/148667964-820f8d27-4115-4fad-834b-61f1bb012d03.png)

## T-Tests on Suspension Coils

The last analysis I performed was to use t-tests to determine if all manufacturing lots and each lot individually were statistically different from the population mean of 1,500 pounds per square inch. The overall lots met the statistical criteria with p-values above .05.  Individually, manufacturing Lots 1 and 2 both met the criteria, but Lot 3 did not. Additionally, the 95% confidence interval for overall, Lot 1, and Lot 2 fall within the 1500 true mean range while Lot 3 does not which further supports this conclusion.  


![t_test_all](https://user-images.githubusercontent.com/90162669/148686804-81218a57-33e4-4199-bf2d-5a6a6fa2fc32.png)

![t_test_lot1](https://user-images.githubusercontent.com/90162669/148686809-67415610-30e9-46dd-b6a7-337d6d3bf072.png)

![t_test_lot2](https://user-images.githubusercontent.com/90162669/148686818-353854d1-767d-4df4-a49b-7c10bf0471e2.png)

![t_test_lot3](https://user-images.githubusercontent.com/90162669/148686827-0a37c953-3469-44bc-8ecb-987d204aa8e2.png)



## Study Design: MechaCar vs Competition

An additional statistical study that could be performed would be to look at fuel efficiency of MechaCars compact vehicles and each of its competitors based on engine size.  This comparison could be done using the one-way ANOVA model.  We would want information regarding vehicle class, fuel efficiency, and manufacturer.  The question we would try to answer would be: “Is there any statistical difference in fuel efficiency between MechaCars compact vehicles and each of our competitors?”  Fuel efficiency will be our dependent, measured variable. The null hypothesis would be that there is no measurable difference, while the alternative hypothesis would be that there is a measurable difference. 
