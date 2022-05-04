
# DESCRIPTIVE STATISTICS

We can divide Statistics field in two categories:
    
Descriptive Statistics and Inferential Statistics.

Descriptive Statistics means summarizing and organizing the data, for example having a lot of data and you want to tell someone about it without giving them all of the data, so you can use indicative numbers.
This is different from Inferential Statistics.
Inferential Statistics means attempting to make inferences  or conclusions from a sample to the whole population.

So using descriptive statistics maybe you want to use a number that is most indicative of all of the numbers in that set. Or some of the numbers that represent the central tendency.

We will begin by listing the measures of central tendency, which represents the idea that there is one number that best summarizes the entire set.

### Measures of central tendency

This measures represent the idea that there is one number that best summarizes the entire set.

**Mean**

The arithmetic mean is probably what you are most familiar with when people talk about average.
If you have five numbers, the mean would be the sum of those five numbers divided by 5.

**Median**

Value that divides data in two equal parts. If the number of elements in the data is even, then the median would be the average of the two middle terms.
When the difference between the consecutive terms is constant (arithmetic progression) then the median = mean.

**Mode**

The mode is essentially what number is most common in a set. If two values appear same time more than others then we have a bimodal set. We can also can trimodal or multimodal sets.

### Measures of variability

This measures represent how spread is the data.

**Standard Deviation**

Standard deviation tells us how far is the mean from each observation in the given data set.

In descriptive statistics we generally deal with data available in a sample, not in a population.

![descriptive_stats_standard_deviation.png](attachment:descriptive_stats_standard_deviation.png)

**Mean Deviation**

The mean deviation gives information about how far the data values are spread out from the mean value.

![descriptive_stats_mean_deviation.png](attachment:descriptive_stats_mean_deviation.png)

**Variance**

Just another measure of dispersion, of how data points differ from the mean. Variance is the expectation of the squared deviation of a random variable from its population mean or sample mean. 

![descriptive_stats_variance.png](attachment:descriptive_stats_variance.png)

**Range**

Range is the difference between the lowest and the highest value.

**Percentile**

It is a way to represent position of a value in data set. To calculate it,  values should always be in ascending order.

12  

24

41   

51  

67  

67   

85   

99

The median 59 has four values less than itself out of eight. 59 is the 50th percentile because 50% of data are less than 59.

**Quartiles**

Quartiles are values that divide your data into quarters. Sorted in ascending order.

![descriptive_stats_quartiles.png](attachment:descriptive_stats_quartiles.png)

12

24

41

51

67

67

85

99

115

Q2 = 67 is 50th percentile of data and is also the median.

Q1 = 41 is the 25th percentile of data.

Q3 = 85 is 75th percentile of data

IQR = interquantile range = Q3 - Q1 

                          = 85 - 41 
                          
                          = 44

### Skewness

![descriptive_stats_skewness.png](attachment:descriptive_stats_skewness.png)

To calculate skewness:

1. Pearson First Coefficient of Skewness (Mode Skewness) 

![descriptive_stats_pearson%20first.png](attachment:descriptive_stats_pearson%20first.png)

2. Pearson Second Coefficient of Skewness (Median Skewness)

![descriptive_stats_pearson%20second.png](attachment:descriptive_stats_pearson%20second.png)

Direction of skewness is given by sign. 0 means no skewness. Negative means negative skewed.
The coefficient compares the sample distribution with a normal distribution.

### Correlation

Statistical technique that can show whether and how strongly pairs of variables are correlated.

Correlation coefficient (r) ranges from -1 to +1.

The closer to +1 or -1, the more closely the two variables are correlated.

If r is close to 0, there is no relationship.

If r is positive, it means that as one variable gets larger, the other gets larger.

If r is negative, it means that as one variable gets larger , the other gets smaller.

### Kurtosis

It is about the existance of outliers.It is a measure of whether the data are heavy-tailed (profusion of outliers) or light-tailed (lack of outliers) relative to a normal distribution.

![descriptive_stats_kurtosis.png](attachment:descriptive_stats_kurtosis.png)

Leptokurtic means tails are thick and heavy
Platykurtic means tails are thinner.

The main difference between skewness and kurtosis is:
    
    Skewness refers to a degree of symmetry.
    Kurtosis refers to a degree of presence of outliers.

References:

https://towardsdatascience.com/understanding-descriptive-statistics-c9c2b0641291
