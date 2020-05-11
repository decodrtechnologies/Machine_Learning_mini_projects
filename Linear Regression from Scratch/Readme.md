# Linear Regression from Scratch 
Linear regression model is built from scratch only for a single attribute dataset using statistical formulas

## License 
The dataset is produced on excel using `NORMINV(RAND(), x, 3)` function and thus is open to use and can be reproduced conveniently by anyone 

## Objective 
To build a linear regression from scratch to correctly predict the target values 

<img src="https://i.stack.imgur.com/SbqXz.png">

## Data Description 
The training dataset is a CSV file with 700 data pairs (x,y). The x-values are numbers between 0 and 100. The corresponding y-values have been generated using the Excel function NORMINV(RAND(), x, 3). Consequently, the best estimate for y should be x.

The test dataset is a CSV file with 300 data pairs

## Libraries Used 
- **numpy**
- **pandas**
- **matplotlib**
- **sklearn**

## Functions Building
Functions for the following operations are built in the notebook : 

     - Mean
     - Variance 
     - Co Variance
     - Coefficients
     - Root Mean Square

## Model Building 

Using the above functions , linear_regression model is built and implemented. The model is evaluated through RMSE scores .

## Conclusion

The plots of dataset and predictions are seen and observed if linear regression is working accurately
