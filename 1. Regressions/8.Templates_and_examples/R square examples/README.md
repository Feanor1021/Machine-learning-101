## WHAT IS R-SQUARED ?

**R-squared** (R2) is a statistical measure that represents the proportion of the variance for a dependent variable that's explained by an independent variable or variables in a regression model. Whereas correlation explains the strength of the relationship between an independent and dependent variable, R-squared explains to what extent the variance of one variable explains the variance of the second variable. So, if the R2 of a model is 0.50, then approximately half of the observed variation can be explained by the model's inputs. The closer it is to 1 the better model. Ofcourse some of the spesicif cases 0.4 can be enough it is depends on the application.

We will use r2_score() function from scikit learn library. It will give us a value from 0 to 1.

from sklearn.metrics import r2_score
r2_score(y_test, y_pred)

You can use these templates for your projects. All you have to do is change the dataset name in the code.

Note : You have to give a data set, which it's first columns are features, last column is dependent variable, and not contain any categorical variable.