### This is an implementation of the Linear Regression Algorithm (in 2 variables)

The method used is quite similar to how SciKit Learn internally operates the algorithm. 

There are 4 functions:

* fit(x, y) : This function takes the training data, that is the part of the data that is used to train the model. It will generate the optimal coefficients 'm' and 'c' that will help in plotting the 'Fit Line'
that is the intuition behind Linear Regression.

* predict(x, m, c): This function takes the testing data (Features only) and the m and c calculated by the fit function. It returns a list/array where each point lies on a straight line that is the Fit Line.

* score(ytrue, ypred) : This function scores are model using the formula of coefficient of determination.

* cost(x, y, m, c): This function calculates the Mean Square Error. 
