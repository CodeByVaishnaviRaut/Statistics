Percentiles and quartiles are measures that help us understand the distribution of data in a dataset. They divide the data into parts based on specific percentages or portions.

### 1. Percentiles:

- **Definition:** Percentiles divide a dataset into hundredths (or hundred equal parts). For example, the 50th percentile is the value below which 50% of the data falls.
- **Formula:** To find the \( p \)th percentile:
  1. Arrange the data in ascending order.
  2. Calculate the rank of the \( p \)th percentile:<img width="170" alt="image" src="https://github.com/CodeByVaishnaviRaut/Statistics/assets/160324454/13981fe8-bf85-4d4c-a6f2-83115359ac02">
, where \( n \) is the number of data points.
  3. If the rank is an integer, the \( p \)th percentile is the value at that rank. If the rank is not an integer, interpolate(calculate mean and find value) between the nearest values.

### 2. Quartiles:

- **Definition:** Quartiles divide a dataset into four equal parts. There are three quartiles: Q1 (25th percentile), Q2 (50th percentile, also known as the median), and Q3 (75th percentile).
- **Formula:** To find the quartiles:
  1. Arrange the data in ascending order.
  2. Calculate the rank of each quartile: <img width="170" alt="image" src="https://github.com/CodeByVaishnaviRaut/Statistics/assets/160324454/ec94c4f9-a1d3-4b7a-b156-8807282586be">
, where \( p \) is 25, 50, or 75, and \( n \) is the number of data points.
  3. If the rank is an integer, the quartile is the value at that rank. If the rank is not an integer, interpolate between the nearest values.

### Summary:

- Percentiles divide data into hundredths and help you understand the relative position of a value in a dataset.
- Quartiles divide data into four equal parts and provide insights into the distribution of data across quarters.
- Both percentiles and quartiles are useful for understanding the spread and distribution of data, especially in large datasets where individual values may not be easy to interpret.
