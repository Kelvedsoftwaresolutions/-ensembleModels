# ensembleModels
ensembleModels

# What is ensemble?
Multiple models working together.

# 4 types
1. Bagging - reduce high variance
2. Boosting - reduce high bias
3. Stacking
4. Cascading

# Aggregation types
1.classification - max
2 Reggression - mean / median

# Bootstrap Sampling
1. Sampling with replacement - sample in sample sets can repeat
2. Build model for all the sample sets

# Bagging: Low (Bias -> (overfitting and underfitting)) and High (Variance -> (How much model changes))

1. Purpose: to reduce variance by using bagging concept
2. Bagging can reduce variance in a model without impacting the bias
3. Model Error / Generalised Error = Bias^2+Variance + error

# Random Forest - always better than bagging

1. Decision Tree + Bagging + Column Sampling + Row Sampling
2. Decision Tree - Base Model
3. Row Sampling with replacement 
4. Column or Feature sampling (Root node or node) with replacement
5. No of observations should be > no of samples

Random Forest Error
1. OOB - out og bag

# Extremely Randomised Tree
1. Decision Tree + Bagging + Column Sampling + Row Sampling + randomized selection (threshold value)
