## Objective:

Use this tool to find which columns to KEEP or DROP as you head into the AI modeling stage of your project.
Drop columns based on missing vaues and correlation analysis to save on processing time and to further clean your data.

## Description 

This tools allows users to perform Featrue Selection based on missing vaues handling,correlation analysis and columns uniques level checks

It Implements different methods to identify features features

1. Features with a high percentage of missing values: This module identify features with a fraction of missing values above a specified threshold .

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/missing_values.JPG)

2. Collinear (highly correlated) features : This module identify collinear features are highly correlated with one another based on a specified correlation coefficient value. Correlation leads to  due to high variance and less model interpretability

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/Correlation.JPG)

3. Features with a single unique value : This module identify any columns that have a single unique value. A feature with only one unique value cannot be useful for machine learning because this feature has zero variance. 

## Advantages:

1.Increases machine learinig model interpretability

2.Reduces computation and training time by Less data means that algorithms train faster.


