# Regression-Feature-selection

### Selecting the correct features:
- Reduces overfitting
- Improves accuracy
- Increases interpretability
- Reduces training time

### Feature selection methods
- Filter: Rank features based on statistical performance
- Wrapper: Use an ML method to evaluate performance 
  * Forward selection (LARS-least angle regression): Starts with no features, adds one at a time
  * Backward elimination: Starts with all features, eliminates one at a time
  * Forward selection/backward elimination combination (bidirectional elimination)
  * Recursive feature elimination: RFECV
- Embedded: Iterative model training to extract features 
  * Lasso Regression
  * Ridge Regression
  * ElasticNet
- Feature importance: tree-based ML models
  * Random Forest --> `sklearn.ensemble.RandomForestRegressor`
  * Extra Trees --> `sklearn.ensemble.ExtraTreesRegressor`
  * After model fit --> `tree_mod.feature_importances_`




