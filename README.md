# Learn_basic_stats_for-Data_science

## Mean
## MEdian
## Mode
## Skewness
## Kurtosis

## The Difference Between Standard Deviation and Average Deviation

### Standard Deviation Versus Average Deviation
Two of the most popular ways to measure variability or volatility in a set of data are standard deviation and average deviation, also known as mean absolute deviation. Though the two measurements are similar, they are calculated differently and offer slightly different views of data.

Determining volatility—that is, deviation from the center—is important in finance, so professionals in accounting, investing, and economics should be familiar with both concepts.

#### KEY TAKEAWAYS
+ Standard deviation is the most common measure of variability and is frequently used to determine the volatility of financial instruments and investment returns.
+ Standard deviation is considered the most appropriate measure of variability when using a population sample, when the mean is the best measure of center, and when the distribution of data is normal.
+ Some argue that average deviation, or mean absolute deviation, is a better gauge of variability when there are distant outliers or the data is not well distributed.

### Understanding Standard Deviation
Standard deviation is the most common measure of variability and is frequently used to determine the volatility of markets, financial instruments, and investment returns. To calculate the standard deviation:

+ Find the mean, or average, of the data points by adding them and dividing the total by the number of data points.
+ Subtract the mean from each data point and square the difference of each result.
+ Find the mean of those squared differences and then the square root of the mean.

Squaring the differences between each point and the mean avoids the issue of negative differences for values below the mean, but it means the variance is no longer in the same unit of measure as the original data. Taking the square root means the standard deviation returns to the original unit of measure and is easier to interpret and use in further calculations.

### Average Deviation
The average deviation, or mean absolute deviation, is calculated similarly to standard deviation, but it uses absolute values instead of squares to circumvent the issue of negative differences between the data points and their means.

To calculate the average deviation:

+ Calculate the mean of all data points.
+ Calculate the difference between the mean and each data point.
+ Calculate the average of the absolute values of those differences.

### Standard Deviation Versus Average Deviation
Standard deviation is often used to measure the volatility of returns from investment funds or strategies because it can help measure volatility. Higher volatility is generally associated with a higher risk of losses, so investors want to see higher returns from funds that generate higher volatility. For example, a stock index fund should have relatively low standard deviation compared with a growth fund.

The mean average, or mean absolute deviation, is considered the closest alternative to standard deviation. It is also used to gauge volatility in markets and financial instruments, but it is used less frequently than standard deviation.

According to mathematicians, when a data set is of normal distribution—that is, there aren't many outliers—standard deviation is generally the preferable gauge of variability. But when there are large outliers, standard deviation registers higher levels of dispersion (or deviation from the center) than mean absolute deviation.

## Percentile vs. Quartile vs. Quantile: What’s the Difference?

Three terms that students often confuse in statistics are percentiles, quartiles, and quantiles.

Here’s a simple definition of each:

Percentiles: Range from 0 to 100.

Quartiles: Range from 0 to 4.

Quantiles: Range from any value to any other value.

Note that percentiles and quartiles are simply types of quantiles.

Some types of quantiles even have specific names, including:

+ 4-quantiles are called quartiles.
+ 5-quantiles are called quintiles.
+ 8-quantiles are called octiles.
+ 10-quantiles are called deciles.
+ 100-quantiles are called percentiles.
+ Note that percentiles and quartiles share the following relationship:

+ 0 percentile = 0 quartile (also called the minimum)
+ 25th percentile = 1st quartile
+ 50th percentile = 2nd quartile (also called the median)
+ 75th percentile = 3rd quartile
+ 100th percentile = 4th quartile (also called the maximum)
