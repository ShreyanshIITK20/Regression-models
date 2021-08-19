# Regression models

## Motive
This repository is created as a part of recuitment task for institue's programming club. 
It mainly focusses on basic understanding of machine learning and implementation of regression algorithm from scratch. 

## Task
To train regression models (linear and polynomial) on the basis of non-standard loss functions 
<li>| y - y<sub>p</sub> |<sup>3
<li>| y - y<sub>p</sub> |<sup>
<li>| y - y<sub>p</sub> |<sup>7
<li>| y - y<sub>p</sub> |<sup>4

## Linear regression
__Original parameters for dataset__ :
<li> Slope : 2.34
<li> Intercept : 1.67
<li> Gaussian noise included

### 1. Optimization by cubic loss function
<li> Slope : 2.36
<li> Intercept : 0.05

![screenshot1](/images/ml1.png)

### 2. Optimization by linear loss function
<li> Slope : 2.37
<li> Intercept : 0.03

![screenshot1](/images/ml2.png)

## Polynomial regression
__Original parameters for dataset__ :
<li> Coefficient of x<sup>2</sup> : 2
<li> Coefficient of x : 3
<li> Constant term : 8
<li> Gaussian noise included

### 1. Optimization by 4<sup>th</sup> degree loss function
<li> Coefficient of x<sup>2</sup> : 1.97
<li> Coefficient of x : 0.02
<li> Constant term : 0.0002

![screenshot1](/images/ml3.png)

### 2. Optimization by 7<sup>th</sup> degree loss function
<li> Coefficient of x<sup>2</sup> : 2.13
<li> Coefficient of x : 0.02
<li> Constant term : 0.0002

![screenshot1](/images/ml4.png)
