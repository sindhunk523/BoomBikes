# BoomBikes
> Boombikes who is bike sharing provider has suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Linear Regression Algorithm is used to identify the impact of the count of bikes rented which inturn has an impact on the revenue.
- The following Steps are performed ; 
1) Data visualisation /Data exploration 
2) Train - Test Split
3) Scaling of numerical variables 
4) dummy variables creation for categorical variables
5) Modelling & feature selection - Recursive feature elimination , p-value checks , VIF checks 
6) Test data prediction 
7) Checking whether residuals or errors are forming a normal distribution when plot with mean at zero and error items have a constant variance  - which is a key assumption for linear -regression algorithm 
8) Comparing R sqare of train and test models simulated.


## Conclusions
- Conclusion 1 
 The linear regression model can be represented as below ;
cnt = 2099.6034 + yr X 1988.66 - holiday X 820 + temp X 4614.32 -hum X 1567.36 -windpeed X 1623 + summer X 910.94 
+ winter X 1175.73+ Aug X 511.27 + Sep X 1112.47 + Oct X 335.62 -Mist X 474 -Light_snow X 2087

- Conclusion 2 

The r2 square for train and test are comparable
train = 83.6% test = 78.22%
The difference is in the allowed range of ~ 5%

- Conclusion 3 
The most impactful  features are - temp , yr and Sep month.

## Technologies Used
- Python 3 Pandas , Numpy , 
- seaborn ,matplotlib.pyplot 
- sklearn libraries 



## Acknowledgements

- This project was based on the assignment on linear regression as part AI/ML program from upgrad /IIITB.
- Thanks to all faculties involved in online and offline training.


## Contact
Created by [@sindhunk523] -https://github.com/sindhunk523/BoomBikes.git


