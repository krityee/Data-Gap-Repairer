# Data-Gap-Repairer
 Description: Simulating missing data through the MCAR mechanism and then utilize interpolation techniques to recover or estimate the missing values, allowing to work with a more complete dataset for your analysis or modeling. 

Mcar: Missing Completely at Random (MCAR) is one of the mechanisms for missing data. It means that the missingness of data is unrelated to any variables, observed or unobserved. In other words, missing values occur randomly and independently of the data's values.

First, you need to identify which values in your dataset are missing. This can be done by examining the dataset or using data exploration techniques.

In this process, we have intentionally corrupted the dataset using MCAR technique from 5 percent corrupted data to 15 percent corrupted data.

Here are some interpolation techniques used to fill the missing values.

Linear interpolation is a simple technique that estimates missing values by assuming a linear relationship between data points. It's commonly used for time-series data or data with a clear sequential order.
Pad Interpolation (also known as Forward Fill or Backward Fill):

Pad interpolation involves filling missing values with the most recent (forward fill) or next (backward fill) observed value. This method is suitable for data where missing values can be approximated by adjacent values.
Cubic Spline Interpolation:

Cubic spline interpolation uses cubic polynomials to estimate missing values. It can capture more complex relationships in the data compared to linear interpolation and is often used for smoothing or interpolating noisy data.
Nearest Neighbor Interpolation:

Nearest neighbor interpolation estimates missing values by using the value of the nearest observed data point. This method is useful when you want to maintain the general trends and patterns of the data.

Remember to evaluate the results of the interpolation techniques and consider their impact on your analysis. If the interpolation results in meaningful imputations and doesn't introduce significant bias, then you can proceed with your analysis using the more complete dataset. If you have concerns about the accuracy of the imputed values, you may want to conduct sensitivity analysis or explore other interpolation methods based on the nature of your data and domain expertise.

