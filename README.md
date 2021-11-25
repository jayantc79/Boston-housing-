# Boston housing prediction
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. This data was collected in 1978 and each of the 506 entries represents aggregate information about 14 features of homes from various suburbs located in Boston.

Our task is to create a machine learning model which can predict the average price of house based on its characteristics.

In the below case study I will discuss the step by step approach to create a Machine Learning predictive model in such scenarios.

# Defining the problem statement:
Create a predictive model which can predict the price( MEDV ) of a house

Target Variable: MEDV(PRICE)

Predictors: CRIM, ZN, INDUS, CHAS, NOX, RM, etc.

# Determining the type of Machine Learning
Based on the problem statement we can understand that we need to create a supervised ML Regression model, as the target variable is Continuous.

Number of Attributes: 13 numeric/categorical predictive

Median Value (attribute 14) is usually the target

Attribute Information (in order):

CRIM per capita crime rate by town

ZN proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS proportion of non-retail business acres per town

CHAS Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX nitric oxides concentration (parts per 10 million)

RM average number of rooms per dwelling

AGE proportion of owner-occupied units built prior to 1940

DIS weighted distances to five Boston employment centres

RAD index of accessibility to radial highways

TAX full-value property-tax rate per $10,000

PTRATIO pupil-teacher ratio by town

B 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

LSTAT % lower status of the population

MEDV Median value of owner-occupied homes in $1000's
