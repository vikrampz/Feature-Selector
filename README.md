## Feature-Selector Plugin

### Why Feature Selection is important ?


1.  Minimize Curse of Dimensionality: It is best weapon to reduce the number of features considerably to boost the model’s performance and to arrive at an optimal solution for the model

2. Reduces Computation and Training Time: Less data means that algorithms train faster.

3. Reduces Overfitting: Less redundant data means less opportunity to make decisions based on noise.


### Plugin Modules

### 1. Advanced Feature Selection

This Plugin allows users to perform Featrue Selection using based on the self selected-algorithm and validation method using Recursive feature elimination with cross validation


#### Recursive feature elimination with cross validation

As the name suggests, this algorithm eliminates worst performing features in each iteration.It works on backward elimination to identify and removes the weakest features until the specified number of features is reached. 

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/Backward_Elimination.JPG)


Feature ranking with recursive feature elimination and cross-validated selection also finds optimal number of features.

Example : Simple visualization for RFE with cross validation score of determine optimal number of features.

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/RFECV.JPG)


### 2.Basic Feature Selection
This Plugin allows users to perform  Featrue Selection based on missing vaues handling,correlation analysis and columns uniques level checks

It Implements different methods to identify features features

1. Features with a high percentage of missing values: This module identify features with a fraction of missing values above a specified threshold .

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/missing_values.JPG)

2. Collinear (highly correlated) features : This module identify collinear features are highly correlated with one another based on a specified correlation coefficient value. Correlation leads to  due to high variance and less model interpretability

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/Correlation.JPG)

3. Features with a single unique value : This module identify any columns that have a single unique value. A feature with only one unique value cannot be useful for machine learning because this feature has zero variance. 
