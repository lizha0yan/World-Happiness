# World-Happiness
## Research of “World Happiness” using linear regression
Selected and preprocessing the data, chose the factors that we wanted to study.
Summarized data and applied regression analysis though R to fit the multiple regression model.
Used the regression model to predict and compared with the actual value.
# Data Collection and Preparation
World Happiness Report 2015 from official website http://worldhappiness.report
Happiness scores from 143 following by 8 factors: 
Log GDP per Capita
Social Support 
Healthy Life Expectancy at Birth
Freedom to make life choice
Generosity
Perception of Government Corruption 
Positive Affect
Negative Affect
Then we remove all the NA values and investigate the predictors
#  Model Selection
AIC test 
Linear Regression
# Model Diagnosis 
Residuals are independent
Residuals are normally distributed
Residuals have equal variance
Except Health has lack of fit, residuals vs. all other predictors in the model fit the null plot
Model fits data well without significant outliers
14th and 96th data have the largest influence
# Model Validation
Overview data between 2015 and 2016
Use linear regression model to predict 2016 data

Some sample graphs:
![alt text](https://github.com/lizha0yan/World-Happiness/blob/master/Graphs/HS_vs_Predictor.png)
![alt text](https://github.com/lizha0yan/World-Happiness/blob/master/Graphs/HSworldmap2016.png)
![alt text](https://github.com/lizha0yan/World-Happiness/blob/master/Graphs/Residual%20Analysis.png)
![alt text](https://github.com/lizha0yan/World-Happiness/blob/master/Graphs/HS_Boxplot%20by%20Region2015.png)
