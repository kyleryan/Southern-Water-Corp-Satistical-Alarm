<h1> Southern Water Corp Python Statistics Case Study</h1>

In this Case Study, we're going to work with Pump Data from Southern Water Corp and using Python's plotting and modelling libraries our goal is to create an alarm model which, using statistically significant variables, should predict Pump Failure.


# Part I: <span style="color:green">Descriptive Statistics</span>
I will need the following libraries for my analysis: 

**Matplotlib** - This is Python's basic plotting library. 

**Seaborn** - This library will enable you to create aesthetically pleasing plots.

**Pandas** - This library will enable you to view and manipulate your data in a tabular format.

**statsmodels.api** - This library will enable you to create statistical models, specifically performing regession analysis


Create Box Plots and Line Plots of Raw and StDev datasets

Create Quartiles and IQR / Identify Outliers

Individually plot each variable against Pump Failure (both Raw and StDev), and again with a time filter based on the index


# Part II: <span style="color:green">Inferential Statistical Analysis</span>

Create correlation Heatmap for both Raw and StDev datasets, the bar plot the variables against Pump Failre to find the most highly/strongly correlated

Create multivariate regression model using both Raw and StDev datasets, then identify which model is more accurate and extract the correlated variables coefficients

Plot the accurate model's predictions against the correlated variables and against pump failure

