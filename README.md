Interquartile Range (IQR)
The Interquartile Range (IQR) is a measure of statistical dispersion and is used to describe the spread of the middle 50% of values in a dataset. It is calculated as the difference between the first quartile (Q1) and the third quartile (Q3):Interquartile Range (IQR)
The Interquartile Range (IQR) is a measure of statistical dispersion and is used to describe the spread of the middle 50% of values in a dataset. It is calculated as the difference between the first quartile (Q1) and the third quartile (Q3):
IQR = Q3 - Q1
Explanation
First Quartile (Q1): The value below which 25% of the data falls.
Third Quartile (Q3): The value below which 75% of the data falls.
The IQR is particularly useful for identifying outliers in a dataset. Values that fall below Q1 - 1.5 × IQR or above Q3 + 1.5 × IQR are often considered outliers.
Example
Consider the dataset: [1, 3, 5, 7, 9, 11, 13, 15, 17, 19]

Q1: 4 (the median of the lower half: [1, 3, 5, 7, 9])
Q3: 16 (the median of the upper half: [11, 13, 15, 17, 19])
IQR = 16 - 4 = 12
The IQR can be visualized using a box plot, where the box represents the range between Q1 and Q3, and the "whiskers" extend to the smallest and largest values within 1.5 times the IQR from the quartiles.

Uses
Identifying Outliers: Values outside 1.5 times the IQR from the quartiles are potential outliers.
Comparing Distributions: The IQR provides a measure of variability that is less sensitive to extreme values compared to the range.
By focusing on the middle 50% of the data, the IQR offers a robust summary of the data's dispersion, making it a valuable tool in exploratory data analysis.
