# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle length and ground clearance have a non-random amount of effect.

### Is the slope of the linear model considered to be zero? Why or why not?
The value of R-squared is greater than 0.5 therefore, since R-squared fits the trend of the data, the slope of the linear model is considered to be greater than zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model effectively pedicts mpg of MechaCar prototypes because the R-squared value is greater than 0.5. The adjusted R-squared values is 0.6825.

## Summary Statistics on Suspension Coils
Overall Summary

![image](https://user-images.githubusercontent.com/91761393/161443406-0b5c72bc-816e-4994-a0ee-f2de63c07e19.png)

The variance of all PSI tolerances on all suspension coils falls within acceptable parameters.

Lot Summary

![image](https://user-images.githubusercontent.com/91761393/161443432-a4c727db-e7a8-4f59-a92f-689f590f921b.png)

Lots 1 and 2 fall under acceptable PSI variance parameters, but Lot 3 has a variance of 170 PSI, which is outside of the acceptable range. 

## T-Test on Suspension Coils

### T-Test on Whole Population

![image](https://user-images.githubusercontent.com/91761393/161443625-86ee8861-eb1a-4ab9-a810-781c14e8e402.png)


### T-Test on Lot 1

![image](https://user-images.githubusercontent.com/91761393/161443610-e5474cb0-b68e-457b-b041-bb806f8f68e0.png)



### T-Test on Lot 2

![image](https://user-images.githubusercontent.com/91761393/161443633-a8e73425-57ed-465f-bc13-a55791bd75a1.png)



### T-Test on Lot 3

![image](https://user-images.githubusercontent.com/91761393/161443645-5f4426a9-dc55-4b44-8c75-d9f9556ad01e.png)


### Summary
For the T-test across all manufacturing lots, the p-value is above the significance value. This means we cannot rule out that randomness is affecting our test results. The same result applies to Lots 1 and 2 given that their p-values are 1 and 0.6072, respectively. Lot 3 falls below 0.5 signifcance value with a p-value of 0.04168, which means that Lot 3's testing is the only sample that can be explained outside of random results. 

##

