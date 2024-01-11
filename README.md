# Housing data analysis 
![37d9f91adbd3889172aa2c88392ebbd49e2b1a82](https://github.com/ab-techz/Housing-data/assets/142206534/bf9dbac0-90cb-4d9d-a7ed-1596c27d59d3)

## Introduction 
This project include the Analysis of the Boston Housing Dataset. Starting off with the Exploratory Data Analysis we try to gather some insights and in the end a Multiple linear regression model has been integrated to predict the prices the houses.(check out the .ipynb file to explore more)

## About the dataset

The dataset describes various town characteristics in Boston, including crime rates, land zoning, business proportions, environmental factors, housing features, and socio-economic indicators. The target variable, MEDV, represents median home values.

- crim - per capita crime rate by town

- zn - proportion of residential land zoned for lots over 25,000 sq.ft

- indus - proportion of non-retail business acres per town

- chas - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

- nox - nitric oxides concentration (parts per 10 million)

- rm - average number of rooms per dwelling

- age - proportion of owner-occupied units built prior to 1940

- dis - weighted distances to five Boston employment centres

- rad - index of accessibility to radial highways

- tax - full-value property-tax rate per USD 10,000

- ptratio - pupil-teacher ratio by town

- black - proportion of blacks by town

- lstat - percentage of lower status of the population

- medv - median value of owner-occupied homes in USD 1000’s

## Insights
 ![download](https://github.com/ab-techz/Housing-data/assets/142206534/e41bfc18-7a00-4efb-9761-d197c0fceeb2)

- The median value of owner-occupied homes in Boston suburbs ranges from $5,000 to $50,000, with a mean of $22,533.
  
- The distribution of median home values exhibits a slight right-skew, characterized by a few suburbs with exceptionally high median values, reaching up to $50,000.

-In areas where the distance to employment centers is within 2-3km, the proportion of black residents varies, with some areas having a lower and others a higher concentration of black residents.

- The crime rate per capita variable has a skewed distribution, with a few suburbs having a very high crime rate compared to others.

- The Charles River dummy variable (which indicates whether a suburb borders the river or not) has a significant impact on the median value of homes, with suburbs that border the river tending to have higher median home values.
    
-Areas farther from employment centers tend to have better air quality due to lower nitrogen oxide concentration compared to those closer to employment centers.
The population with a lower-class percentage between 10% and 36% is responsible for the majority of crimes.

- Affordable housing is available in all areas regardless of air quality, while expensive housing is only found in areas where the air quality falls within an acceptable range, specifically between 0.4 and 0.65.

- The index of accessibility to radial highways varies greatly among different areas, with some having an index below 5 and others close to 25, indicating regional disparities.

- The distribution of median home values in suburbs is roughly bell-shaped, with most suburbs having median home values between 10,000 and 40,000.
