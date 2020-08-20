# Predict total count of bikes rented by both casual users and members of Capital Bikeshare using predictive analysis

<b> About the project: </b>

    Capital Bikeshare has about 30K members, and served about 23.6 million trips through its 550 stations. 
    The Bikeshare data has been combined with weather data to gather better insights for prediction.
    
    There are two main objectives. 
      First, to predict the variable COUNT as a function of the other variables. 
      Second, to build alternative models, and measure and improve the performance.
  
<b> About the data set: </b> </br>
The data set used in this assignment is <i><b> bikeShare.csv </b></i> from DC’s <b> Capital Bikeshare </b> (also serves Maryland and Virginia). </br>
Data Dictionary:
![](Images/Data_dictionary.PNG)<br/>

<b> Libraries to download: </b> </br>

    tidyverse
    tidymodels
    plotly
    skimr
    caret

<b> Steps in the notebook:</b> </br>

    1. Data Preparation
        - Creating new variables
        - Standardizing variables
    2) Exploratory analysis 
    3) Run a Linear Regression model for COUNT using MONTH, WEEKDAY, BADWEATHER, TEMP, ATEMP, and HUMIDITY and regression diagnostics
    4) Run a linear regression to determine the effect of bad weather on COUNT
    5) Run a linear regression to determine the effect of bad weather and week day (Interaction Variable) on COUNT
    6) Split dataset into training and test set (80% and 20% respectively) and perform predictive analysis
    7) Perform time series analysis on training and test data.
    
  The code can be found in the pdf doc named <i> <b> Assignment_2_report </b> </i>
