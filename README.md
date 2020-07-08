# DataScience
Comparison of classification models for calculating churn prediction

Steps:

1-) List use cases for our dataset.<br>
2-) Choose one use case: churn predicition, because this is one of the most important metrics for the company.<br>
3-) Before starting any analysis, we perform a descritive analysis of data in order to make transformation, as we did in 'register_date' and removing NaN, outliers and duplicate data.<br>
4-) Reducing dimensionality through PCA.<br>
5-) We chose 5 components (it gives a 70% data variance explaining). To choose which components we use, we aplly a Random Forest classification and then we get the important features for our model.<br>
6-) Run 6 different models and pick the one with best accuracy.
