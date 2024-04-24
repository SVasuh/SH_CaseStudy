# Surprise-Housing Price Prediction Case Study

Surprise Housing, a US-based housing company, has decided to join the Australian market. The organization employs data analytics to buy houses at a lower price than their true value and resell them at a higher price.

The company is seeking for potential properties to purchase in order to enter the market. The requirement is to create a regression model with regularisation in order to estimate the actual value of potential properties and determine whether or not to invest in them.
The organization seeks to determine which characteristics accurately forecast housing prices.



## Study By
- Vasudha Srinivasaiah

## Table of Contents
* Problem Statement
* Business Understanding
* General Info
* Conclusions
* Technologies Used
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->
## Problem Statement

The organization seeks to determine

    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.



## Business Understanding

The business expects the analyst to model housing prices using the relevant independent factors. This model will then be utilized by management to determine how prices fluctuate with the factors. They can then modify the firm's strategy to focus on regions that will generate large profits. Furthermore, the model would help management comprehend the pricing dynamics of a new market.

## General Information

- Steps for EDA :
- Data Understanding
- Data Preperation 
- Data Visualisation
- Model Building
- Model Evaluation
- Prediction
- Prediction Evaluation
- Conclusion
- Data Set :  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Model Building was done using Lasso and Ridge Regression.
Top 5 Features influencing the SalesPrice prediction  were
OverallQual    
GrLivArea      
GarageCars     
ExterQual     
KitchenQual 

The Optimal The optimal value of alpha for ridge and lasso regression
Ridge Alpha : 9.739119536819391
Lasso Alpha : 0.018301662744060254

From Evaluation
Lasso R2-Score :
R2 Train  : 0.8247993965906161
R2 Test   : 0.8481174146330043
MSE Train : 0.16525235030440807
MSE Test  : 0.17195560598470203

Ridge R2-Score :
R2 Train  : 0.8387614274901314
R2 Test   : 0.8373014919006796
MSE Train : 0.1520831124349676
MSE Test  : 0.18420097659928966


R2 Lasso Score in %age 
Train --> 82.48%  
Test  --> 84.81%

Ridge R2 Score in %age
Train --> 83.88%  
Test  --> 83.73%


## Technologies Used

- Pandas - 2.0.3
- Numpy - 1.24.3
- Matplotlib - 3.7.2
- Seaborn - 0.12.2
- Plotly - 5.9.0
- scikit-learn - 1.3.0
- statsmodel.api - 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project is individual case study for an online advance course.
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://scikit-learn.org/
- https://www.statsmodels.org/



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
