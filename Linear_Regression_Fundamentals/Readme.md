
What is Linear Regression?

It’s a method to predict a target variable by fitting the best linear relationship between the dependent and independent variable.<br>
                                  y=mx+c
<br>
### What is the Best Fit?

It can be of any shape depending on the number of independent variables (a point on the axis, a line in two dimensions, a plane in three dimensions, or a hyperplane in higher dimensions).
Least Squares Method: The best fit is done by making sure that the sum of all the distances between the shape and the actual observations at each point is as small as possible. The fit of the shape is “best” in the sense that no other position would produce less error given the choice of shape.
If you want to go into the mathematics, you can have a look below or if you hate mathematics, just skip!
Least Squares Method for Simple Linear Regression.

![]("https://miro.medium.com/max/766/1*sptOVkwL9NwaRfjDL_6y7w.png")

Note: I have shown this method only for Simple Linear Regression. You may extend it for Multiple Linear Regression. Don’t know what Simple and Multiple Linear Regressions are? No problem, keep reading.
Application in Real Life


### Types of Linear Regression

Yes, we are complicating it for you. Be open to new stuff. :D
1. Simple Linear Regression

This method uses a single independent variable to predict a dependent variable by fitting a best linear relationship.
2. Multiple Linear Regression

This method uses more than one independent variable to predict a dependent variable by fitting a best linear relationship.

In case of Multiple Regression, the parameters can be found in the same way as that in the case of simple linear regression, by minimising the cost function using:

### Gradient Descent

Given a function defined by a set of parameters, Gradient Descent starts with an initial set of parameter values and iteratively moves towards a set of values that minimise the function. This iterative minimisation is done using calculus, taking steps in the negative direction of the function gradient.

Note: It works best when multicollinearity is absent. It’s a phenomenon in which two or more predictor variables are highly correlated.

### Stepwise Regression

This regression model is used when we have more than one independent variable. It uses automatic procedure to select important independent variables and there is no human intervention.

### Forward Stepwise Regression

Here, we start with null model which means it has no predictors, just one intercept (the mean over dependent variable).
Now, fit p(total number of variables) simple linear regression models, each with one of the variables in. Thus, we have just searched through all the single variable models, the best one and fixed this one in the model.Similarly, search through the remaining p-1 variables one by one, but this time with that variable in the model which was selected in previous step. Now choose the model which will be best among the p-1 models.Continue until some stopping rule is satisfied like some threshold value of the number of variables to be selected.

Backward Stepwise Regression

It starts with the full least squares model containing all p predictors. Now remove the variable with the largest p-value i.e. the least significant predictor. The new model shall have (p-1) variables. Remove the variable with largest p-value again. Continue until some stopping rule is satisfied like all variables have a p-value smaller than a threshold value. 

So you can see, Stepwise Linear Regression is applying Multiple Linear Regression multiple times and selecting the important variables or removing the least significant predictors each time.

Note 1: For Backward Stepwise Linear Regression or Multiple Linear Regression to work fine, the number of observations (n) should be more than the number of variables(p). It is because we can do least squares regression only when n is greater than p. For p greater than n, least squares model is not even defined.

Note 2: Automatic procedures may not choose the right significant variables from practical point of view as they don’t have the special knowledge the analyst might have.
