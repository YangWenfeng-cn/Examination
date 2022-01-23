# **Questions to Examination the course «Mathematical methods in forecast» Prof. Yaroslavna Pankratova** 

# 1 Give the definition of a time series. What is a strictly stationary time series? 

**给出时间序列的定义。 什么是严格平稳的时间序列？**

**A time series** is a sequence of numerical data points taken at successive(adj. 连续的) points in time , normally at uniform(adj.均匀的) intervals. We consider **a discrete(adj.离散的) time series** with **a fixed interval** called by a step. 

A stochastic(adj.随机) process is called **strictly stationary** if a joint probability distribution of m observations is the same as for the observations for arbitrary time moments. And k>0. In other words, time series properties do not change when you change the origin. 

# 2 Give the definition of a time series. What is a weakly stationary time series? 

***A time series\*** is a sequence of numerical data points taken at successive points in time , normally at uniform intervals. We consider ***a discrete time series\*** with ***a fixed interval\*** called by a step. 

A stochastic process is called ***weakly stationary\*** if : 

1. its mathematical expectation and variance are constant over time, so  $$E(y_t) = \mu, Var(y_t) = E(y_t-\mu)^2 = \sigma_y^2;$$

2) a value of the covariance between two observations of a time series depends only on the distance between these observation (the lag). 

# 3 What is autocorrelation function and private autocorrelation functions? Name their applications. 

The covariance vetween $$y_t$$ and its value at another time period, say, $$y_{t+k}$$ is called the **autocovariance** at lag k, defined by 
$$
\gamma_k = Cov(y_t,y_{t+k}) = E{(y_t-\mu)(y_{t+k}-\mu)}
$$
The collection of the values of $$y_k$$, k = 0,1,2,... is called the **autocovariance function.** Note that the autocovariance at lag $$k=0$$ is just the variance of the time series, that is, $$\gamma_0 = \sigma_y^2$$. 

# 4 What is "white noise"? 

# 5 Describe an autoregressive process of order p. Under which condition is the process the AR(1)- process stationary? 

# 6 What are the relations between the coefficients of the equation for the AR(1)-process and the values  of its autocorrelation function?

# 7 What are the relations between the coefficients of the equation of the AR(2)-process and the values  of its autocorrelation function?  

# 8 Describe the moving average process of order q. Under which condition is the process SS(1)  stationary?  

# 9 Let the process $$y_t-\varPhi_1y_{t-1}=\delta+\varepsilon_t-\theta_1\varepsilon_{t-1}$$ be given. Determine the type of this process. Under  which conditions is the process stationary?  

# 10 Describe the process of a random walk and give its properties. 

# 11 Describe the problem of nonstationary time series and its consequences. Give methods for detecting  nonstationarity and correcting the series. 

# 12 What is an integrable time series of order d? 

# 13 What is the evaluation of the quality of ARIMA models? Provide some well-known criteria of the  quality for ARIMA models. 

# 14 Write the following process using the lag operator $$y_t = μ + φ_1y_{t−1}+φ_2y_{t−2} + ⋯ + φ_py_{t−p} + ε_t$$

# 15 List the possible composition of the non-random components of a time series and some methods  for determining their presence in the series. 

# 16 Describe the moving average method. What is it used for? 

# 17 Describe the weighted moving average method. What is it used for? 

# 18 What is the difference between the simple exponential smoothing and the linear exponential  smoothing? 

# 19 What is the essence of Brown's method? What is the multiple exponential smoothing? 

# 20 Write down the Gauss-Markov conditions for a multiple linear regression. 

# 21 Give the definition of the coefficient of determination, its interpretation and applications. 

# 22 Give definitions of a point forecast and an interval forecast. How to calculate the interval forecast  if the point forecast and the standard error of the forecast are given? 

# 23 What is the meaning of the "standard error of a regression coefficient"? 

# 24 Which test is used to check significance of a linear regression equation? 

# 25 Based on which indicators can you judge the quality of coefficients of the regression model? 

# 26 What are the standardized coefficients of a multiple regression? What is their meaning? 

# 27 Define and interpret the partial elasticity coefficients. For what purpose are they used? 

# 28 What properties should the errors of the linear regression equation satisfy? 

# 29 What is the method of least squares? 

# 30 The regression y = β0 + β0x + ε is estimated based on two observations. What is the coefficient  of determination? 

# 31 Describe the concept of multicollinearity. Consequences multicollinearity, methods of its detection  and ways to get rid of multicollinearity. 

# 32 Give the definition of the coefficient of determination and the adjusted coefficient of determination.  What is their difference? Application area