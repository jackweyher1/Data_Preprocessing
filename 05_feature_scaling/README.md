This directory will be used for practicing feature scaling, such as normalization and standardization, in the data preprocessing stages of machine learning.

Below is a list of the different feature scaling techniques 

1. Min-Max Scaling (Normalization)
Scales values to a fixed range, usually [0, 1]
Best for: when you need bounded values, neural networks, KNN
Sensitive to outliers

2. Standardization (Z-Score Scaling)
Centers data around mean=0 with std=1
Best for: most ML algorithms, when data is normally distributed
Less sensitive to outliers than MinMax


3. Robust Scaling
Uses median and interquartile range (IQR) instead of mean/std, data is scaled around the median
Best for: data with significant outliers
Most outlier-resistant of the common scalers

4. Max Abs Scaling
Scales by dividing by the maximum absolute value, range [-1, 1]
Best for: sparse data, already centered at zero


5. Log Transformation
Reduces skewness in heavily skewed data
Best for: right-skewed distributions, exponential data


6. Power Transformation
Makes data more Gaussian-like
Best for: when normality is required


7. Quantile Transformation
Maps data to a uniform or normal distribution
Best for: non-linear scaling, when you want to force a specific distribution
Most aggressive transformation