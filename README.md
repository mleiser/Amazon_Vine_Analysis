# Amazon_Vine_Analysis

## Overview of the Analysis
  
### Purpose
  The purpose of this project was to use AWS RDS instances to connect to PySpark and PostgreSQL to determine if there is any biases towards favorable reviews on Amazon's Vine program.  This was done using PySpark to ETL the database and Pandas to analyze the data set after loading.
## Amazon Analysis Results
![Vine Analysis Results](https://user-images.githubusercontent.com/46801182/192920042-9153c98a-7f32-491e-bb60-bcae1aede49e.png)
- There were 94 Vine reviews and 40,471 non Vine reviews.
- There were 48 Vine five-star reviews and 15,663 non Vine five-star reviews.
- The total percentage for Vine reviews was 51.06% and 38.70% for non Vine reviews.

## Amazon Analysis Summary
  Based on the analysis, there is a positivity bias with the Vine program. This is seen with the large difference in percentage of five-star reviews when looking at Vine vs non Vine reviews. Another test that could be performed with the data set to support the statement would be to perform statistical analysis such as a T-Test agaist the two datasets to prove that there is a statistically significant difference between the programs.
