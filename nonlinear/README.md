The non-linear regression team is responsible for the following:

Multiple options for non-linear regression
	Parabolic
	Exponential
ACF
PACF

----------------------------------------------------------------------------------------
ACF:
Refer to ACF.py
The pages 38-41 of the textbook were used for this module. Using this module we can get:
- The auto-correlation(formula 2.11)
- The plot of the correlogram

This module could essentially be reused by the box-jenkins team to find the acf.

Contracts:

ACF is for time series data, hence the input is univariant. 
get_correlogram(time_series_data, number_of_lags = 20) is the main function

Input:
- An array of floating values, Y_axis_time_series_data
- Optional input number_of_lags, with default value of 20

Output: 
- Plot of the correlogram
Please note that the output may vary at the time of integration

----------------------------------------------------------------------------------------
