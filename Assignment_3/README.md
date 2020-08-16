# Predict whether a car purchase is a bad buy or not using different predictive models

<b> About the project: </b>

    Auto dealers purchase used cars at auctions with a plan to sell them to consumers, 
    but sometimes these auctioned vehicles can have severe issues that prevent them from being 
    resold at a profit (called, lemons). 
    
    There are two main objectives. 
      First, to predict the variable BadBuy as a function of the other variables. 
      Second, to build alternative models, and measure and improve the performance.
  
<b> About the data set: </b> </br>
The data set used in this assignment is <i><b> carvana.csv </b></i> which contains data from 10,062 car auctions as provided by <b>Carvana</b>. </br>

<b> Libraries to download: </b> </br>

    tidyverse
    tidymodels
    plotly
    skimr
    caret

<b> Steps in the notebook:</b> </br>

    1. Data Preparation
    2) Exploratory analysis of the training data set
    3) Run a Linear Probability Model to predict a lemon using all other variables
    4) Run a logistic regression model to predict a lemon using all other variables
    5) Run a linear discriminant analysis (LDA) using all variables
    6) Run a kNN model using all variables
    7) Build a lasso model using all variables
    8) Build a Ridge and Elastic net model using all variables
    9) Run a quadratic discriminant analysis (QDA) with all variables
    10) Report the ROC curves for the models on the same chart
    11) Identify which model is better for the given business case/problem
