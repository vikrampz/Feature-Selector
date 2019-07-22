## Feature-Selector Plugin

### Why Feature Selection is important ?

```
1. Feature Selection is best weapon to minize Curse of Dimensionality.It is necessary to reduce the number of features considerably to boost the model’s performance and to arrive at an optimal solution for the model

2. Reduces Computation and Training Time: Less data means that algorithms train faster.

3. Reduces Overfitting: Less redundant data means less opportunity to make decisions based on noise.
```

### Plugin Modules

### 1. Advanced Feature Selection

This Plugin allows users to perform Featrue Selection using based on the self selected-algorithm and validation method using Recursive feature elimination with cross validation


#### Recursive feature elimination with cross validation

As the name suggests, this algorithm eliminates worst performing features in each iteration.It works on backward elimination to identify and removes the weakest features until the specified number of features is reached. 

![alt text](https://github.com/vikrampz/Feature-Selector/blob/master/Backward_Elimination.JPG)


Feature ranking with recursive feature elimination and cross-validated selection of the best number of features.


### 2.Basic Feature Selection
This Plugin allows users to perform  Featrue Selection based on missing vaues handling,correlation analysis and columns uniques level checks

