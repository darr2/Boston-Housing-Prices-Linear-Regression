# Linear Regression

The following project demonstrates fundamental concepts
in better understanding linear regression.

# Description

The following python notebook is an introduction to linear regression fundamentals.
It uses the Boston Housing Prices data set from the <code>sklearn</code> library and is
loaded to the notebook like so: <br />
<code>from sklearn.datasets import load_boston</code><br />
<code>boston = load_boston()</code></p><br />
The column of interest in the data set is the housing price (our output column), and the objective here is
to accurately predict the price of a housing unit given its features.  In particular, we
are intrested in the features that significantly affect the housing prices the most.  In thris project,
we do this by applying linear regression analysis.

Once I apply linear regression to the data set, I then compared models with one another to see which one
fits the data best.  This is done by finding the F-Statistic, its corresponding p-values, and which features 
that plays a significant role in changing the default regression model provided (beta values). Additionally, I 
checked to see if the model used is a good fit for the data, and searched for outliers which may have 
significant leverage on the positioning of the regression. Removing those outliers would then provide a 
better fit to the housing price data for more accurate predictions.
