# Weather_EDA

Provided the weather data ﬁle (Weather_2009_2016.csv). These attributes in the dataset are

1.Temperature (degC)

2.Pressure (mbar)

3.Tdew (degC)

4.rh (%)

5.VPdef (mbar)

6.sh (g/kg)

7.H2OC (mmol/mol)

8.rho (g/m^3)

9.wv (m/s)

10.max. wv (m/s)

11.wd (deg)

The last ten columns are independent variables and the first one is the dependent variable. Assume the linear regression can be denoted as 𝐲=𝑐+𝑎1𝐱1+⋯+𝑎10𝐱10
 
𝑦  is the dependent variable,  𝑥𝑖 's are independent variables,  𝑐  is the constant and  𝑎𝑖  are the coeﬃcients of the linear regression. Please show the coeﬃcients of the linear regression in order (i.e.,  𝑐,𝑎1,𝑎2,...,𝑎10 ) with the following approaches:

Calculate the linear regression from the raw data directly. (You can choose one of the approaches in class for implementation; of course, you must make sure that you won't get a singular matrix if you use the matrix approach.)

Generate a heatmap for the diagonal correlation matrix with attributes and show your observation.

Explore multiple variables with scatter plot. The scatter plot of Pandas is a grid of plots of multiple variables one against the other, showing the relationship of each variable to the others. Please state what you observe.

Improve the linear regression from question 1 and get a new linear regression if the coeﬃcients are meaningless.
