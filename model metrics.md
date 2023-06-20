## Model Metrics
### Features
- used RandomOverSampler to balance features
- final predictive features: click and C21

### Parameters
- Random Forest Model
  - parameters: ('bootstrap': True, 'ccp_alpha': 0.0, 'class_weight': None, 'criterion': 'gini', 'max_depth': None, 'max_features': 'auto', 'max_leaf_nodes': None, 'max_samples': None, 'min_impurity_decrease': 0.0, 'min_samples_leaf': 1, 'min_samples_split': 2, 'min_weight_fraction_leaf': 0.0, 'n_estimators': 100, 'n_jobs': None, 'oob_score': False, 'random_state': None, 'verbose': 0, 'warm_start': False)

### Hyperparameters
- used GridSearchCV for hyperparameter tuning 
  - new hyperparameters: (n_estimators=600, n_jobs=-1, verbose=1)
- final parameters after hyperparameter tuning: (bootstrap=True, class_weight=None, criterion='gini', max_depth=None, max_features='auto', max_leaf_nodes=None, min_impurity_decrease=0.0, min_samples_leaf=1, min_samples_split=2, min_weight_fraction_leaf=0.0, n_estimators=600, n_jobs=-1, verbose=1, random_state=None, warm_start=False, oob_score=False)

### Performance Matrices 
- Accuracy score
- Confusion Matrix 
- ROC-AUC Score & ROC Curve
