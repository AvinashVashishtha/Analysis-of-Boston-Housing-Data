# Analysis-of-Boston-Housing-Data
Simple linear Regression | Best/Stepwise | Lasso | Regression Tree | GAMs | Bagging | Random Forest | Boosting | Neural Network

## Abstract
Objective of this exercise it to predict housing price(medv) using various independent variables given in the data- crime rate, rooms, nitrogen oxides concentration etc

## Findings
Based on Test Error, following order was seen for predictive power 
# Random Forest > Boosting > Neural Network > Bagging >  GAMs > Regression Tree >  Stepwise ~ Simple > Lasso Regression

## Detailed analysis and report

Please find the RPubs link below.
http://rpubs.com/Avinash_19910102/507710

## Data Description 
This data frame contains the following columns:

crim : per capita crime rate by town.

zn : proportion of residential land zoned for lots over 25,000 sq.ft.

indus : proportion of non-retail business acres per town.

chas : Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).

nox : nitrogen oxides concentration (parts per 10 million).

rm : average number of rooms per dwelling.

age : proportion of owner-occupied units built prior to 1940.

dis : weighted mean of distances to five Boston employment centres.

rad : index of accessibility to radial highways.

tax : full-value property-tax rate per $10,000.

ptratio : pupil-teacher ratio by town.

black : 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.

lstat : lower status of the population (percent).

medv : median value of owner-occupied homes in $1000s.

