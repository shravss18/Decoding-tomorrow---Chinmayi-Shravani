# Decoding-tomorrow---Chinmayi-Shravani

Models

MODEL 1 : ARIMA
Arima stands for Auto Regressive Integrated Moving Average
p,d,q are the parameters of the function ARIMA 

PACF - Partial Auto Corelation Graph
the maximum of PACF is the p value

ACF - Auto Corelation Graph
the maximum of ACF if the q value 

Transformation of data to help understand the data:
(i) Differentiation 
(ii) Differencing 
(iii) Logarithmic 
(iv) Exponential 

Number of times we apply any of the above functions = d value 
When we get negative values, we stop applying the functions and the last one is not counted 
AIC - should be less(from model summary)

MODEL 2 : SARIMA 
Sarima stands for Seasonal ARIMA 
It is very similar to ARIMA 
plot ACF and PACF
In ARIMA, we get p,d,q values 
In SARIMA, we get p,d,q,P,D,Q,s values
s-seasonality check 
