# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

 - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 * Vehicle_lenght and ground_clearance seemed to have a non-random amount of variance
 - Is the slope of the linear model considered to be zero? Why or why not?
 * No, the slope is not zero since this is a multiple linear regession model.
 - Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 * The model seems overfit to our data and it can only predict the correct mpg 71% of the time. This would not work well on other datasets
 ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/mecha_summary.PNG)

 ## Summary Statistics on Suspension Coils

 - The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 * The lots, as a whole, collectively met the variance requirements. However, when you take a look at each lot individually, you can see that Lot 3 is not meeting variance requirements at 170. 
 ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/total_summary.PNG)
  ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/lot_summary.PNG)

 ## T-Tests on Suspension Coils
 - If we look at the p-values of the t-tests per lot, lot 3's mean is significantly different that the rest of the lots. Lot 3's p-value is at .041 which is within the accetable .05 threshold. 
 ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/lot1.PNG)
 ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/lot2.PNG)
 ![](https://github.com/JosefMoore/MechaCar_Statistical_Analysis/blob/63322aab5286ec5dd239edaaca96b537ab1ed883/Images/lot3.PNG)