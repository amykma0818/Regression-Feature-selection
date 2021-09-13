# Regression-Feature-selection

### Selecting the correct features:
- Reduces overfitting
- Improves accuracy
- Increases interpretability
- Reduces training time

### Feature selection methods
- Filter: Rank features based on statistical performance
- Wrapper: Use an ML method to evaluate performance 
  * 1. Forward selection (LARS-least angle regression): Starts with no features, adds one at a time
  * 2. Backward elimination: Starts with all features, eliminates one at a time
  * 3. Forward selection/backward elimination combination (bidirectional elimination)
  * 4. Recursive feature elimination: RFECV
- Embedded: Iterative model training to extract features 
 * 1. Lasso Regression
 * 2. Ridge Regression
 * 3. ElasticNet
- Feature importance: tree-based ML models
 * Random Forest --> `sklearn.ensemble.RandomForestRegressor`
 * Extra Trees --> `sklearn.ensemble.ExtraTreesRegressor`
 * After model fit --> `tree_mod.feature_importances_`




