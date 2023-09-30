# Decoding-tomorrow---Chinmayi-Shravani

Business perspectives of Time series forecasting
SGQ stands for Scenario Gap Quest. WHile analysing the data, we make 3 columns - the current scenario, gap, and the future.
The current scenario is simply the current situation of the business in terms of sales etc. 
The duture is the desired situation. The state the company would like to see their sales in. 
Gap is the difference between the current scenario and the future scenario. 
Visual representation always makes it easier to understand the data

Step 1 of representation is: Gap - Finding out all the positive and negative factors that affect the situation (for eg sales of a shoe)
Step 2- Divide the factors from step 1 even further. Micro analyse it even more. 

Hypothesis testing 
There are two statements in hypothesis testing - Null hypothesis and Alternate hypothesis
Always define null hypothesis with the opposite of what you agree on/ what you're trying to prove 
Pvalue = (All values - mean)/Standard deviation 
from the normal distribution curve, we get alpha value. 
For alpa=x, Pvalue=y

From the z-table, we get the z-value
if the z-value>Pvalue, null hypothesis is rejected and the alt hypothesis becomes the final one
if the z-value<Pvalue, null hypothesis is accepted.

Chi square test - When you want to see the co-relation between quantitative aspects. It is used for qualitative data/columns 

ANOVA - Analysis Of Variance 
Variance is compared with Pvalue
Default statements are the null and alt hypothesis
Again, Always define null hypothesis with the opposite of what you agree on/ what you're trying to prove

Seasonality - Refers to predictable changes
Stationality - Doesn't have any trends/ seasonality traits. It doesn't depend upon time 

Tests for Seasonality and Stationality - ADF and KPSS
#ADF - Augmented Dicky-Fuller test
#KPSS

Series - 1 Dimensional
Dataframe - 2 Dimensional 

Box plots - plot data in the form of a box
IQR - Interquartile Range
IQR (value)= Q3-Q1
percentile=np/100 (where n= total no. of values, p - the % we want to find eg:25,50,75)
Upper limit(U.L) = Q3+1.5(IQR)
Lower Limit(L.L) = Q1-1.5(IQR)
Q2- middle
Q1=25%; Q2=50%; Q3=75%

Whatever result we receive from ANOVA is known as Hypothesis testing inference.
This is given to the model along with parameters 

Comparing the parameters and training data, we get Similarity ratio. 
If the similarity ratio is high, hypotuning is required. It'll then access all the finer details 
If the similarity ratio is around 98, that means hypotuning is restricting the model to the 70 values of training data. 

Calculate the MAPE, MAE etc
if MAPE,15% that means, the job is done. we can predict future value
THe future values that we predict is the final output
