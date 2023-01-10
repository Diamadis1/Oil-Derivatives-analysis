# Oil-Derivatives-analysis
I. Data set example

![image](https://user-images.githubusercontent.com/98957437/211608025-11cee3d5-4998-4abf-bb17-dcef3576fe58.png)

II. Value of options over time

![image](https://user-images.githubusercontent.com/98957437/211608196-cc90d509-26b0-4ef2-b8be-a080fdf78e2a.png)

III. Drawing the diagrams with the values of the options as they are each Friday (closing price)

![image](https://user-images.githubusercontent.com/98957437/211608360-58fc041a-31dd-472f-a230-e08a23a91658.png)

IV. Calculating the mathematical equation of the change in the value of two different options over time. (E.g. the one corresponding to (+-4) distance from the pointer and that at a distance of (+-20).

Linear Regression

![image](https://user-images.githubusercontent.com/98957437/211608454-7a75dd1d-0e92-44bc-a608-67f8b051864d.png)

In statistics, linear regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). The case of one
explanatory variable is called simple linear regression; for more than one, the process is called multiple linear regression. This term is distinct from multivariate linear regression, where multiple correlated dependent variables
are predicted, rather than a single scalar variable.
In linear regression, the relationships are modeled using linear predictor functions whose unknown model parameters are estimated from the data. Such models are called linear models. Most commonly, the conditional mean
of the response given the values of the explanatory variables (or predictors) is assumed to be an affine function of those values; less commonly, the conditional median or some other quantile is used. Like all forms of
regression analysis, linear regression focuses on the conditional probability distribution of the response given the values of the predictors, rather than on the joint probability distribution of all of these variables, which is the
domain of multivariate analysis.
In our case we use linear regression in order to estimate the coefficients and intercepts in order to establish our functions for each option given. By observing each function one could easily see that the (+-4) option's coefficient
and intercept are very close while (+-20) option's are very close too. However if we compare the (+-4) and (+-20) option's coefficients and intercepts we could notice that the numbers have a lot of distance between them. Of
course in all four cases (m) has a negative sign that indicates a bearish pattern
![image](https://user-images.githubusercontent.com/98957437/211608656-64cf62f1-72f9-40eb-99c6-c0d39bbfed13.png)

Diagrams of the rate of change of the value of the (+-4) and (+-20) Options as a function of index change

![image](https://user-images.githubusercontent.com/98957437/211609009-70c87ead-8e43-4a96-8ea4-74105e2596c9.png)
![image](https://user-images.githubusercontent.com/98957437/211609049-6b693744-9486-4602-8bfb-531c2a1c790e.png)

V. Estimating the diagrams of the rate of change of the value of the Option (Those who are within ±4 of the pointer as well as those that are at a distance ±20) as a function of index change
![image](https://user-images.githubusercontent.com/98957437/211609144-dc9637ba-7af1-4133-8eaf-51fa28c10d9c.png)

CUBIC SPLINE INTERPOLATION (plots)

![image](https://user-images.githubusercontent.com/98957437/211609230-6af7061e-bea1-4cf0-ac5b-660d4eedb633.png)

VI. Calculating the first differences in the value of the options and plotting the time series for the period examined for (+-4) and (+-20) options
![image](https://user-images.githubusercontent.com/98957437/211609459-32ee8dbe-644f-422a-ae25-c99925e9dd22.png)
![image](https://user-images.githubusercontent.com/98957437/211609512-11f9fdec-0520-4b71-9224-cebce1fcb3d5.png)

VII. Statistical distribution of the log returns while we calculate the mean value of each one of them. In addition, we calculate the confidence intervals 5% of each one
![image](https://user-images.githubusercontent.com/98957437/211609667-d18410fe-de08-429d-b495-3751ee004514.png)
