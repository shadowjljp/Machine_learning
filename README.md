# Machine_learning
Machine learning and AI related to this folder


Car Evaluation through Machine Learning(ML methods comparison).ipynb

According to the tabulate shows above, the XGBoost has the best performance because it has the best performance and training time is relatively short. 
Gradient Boosting Classifier is also pretty close but it takes much more time than XGBoost to trainer.
Alogrithms and best parameters are shown below. More detail in the file.

Algorithms                    Best Parameters                                                                                                                                                    
Decision Tree                 {'max_depth': 1, 'max_features': 1, 'max_leaf_nodes': 10, 'min_impurity_decrease': 1, 'min_samples_leaf': 1, 'min_samples_split': 0.1, 'min_weight_fraction_leaf': 0}        
Neural Net                    {'activation': 'relu', 'alpha': 0.0001, 'hidden_layer_sizes': 100, 'learning_rate': 'constant', 'max_iter': 400}                                                             
Support Vector Machine        {'C': 1000, 'gamma': 0.001, 'kernel': 'rbf', 'max_iter': 1, 'random_state': 0}                                                                                              
Gaussian Naive Bayes          {'priors': [0.3, 0.3, 0.2, 0.2]}                                                                                                                                             
Logistic Regression           {'C': 1.0, 'class_weight': 'balanced', 'fit_intercept': True, 'penalty': 'none', 'solver': 'sag'}                                                                            
k-Nearest Neighbors           {'algorithm': 'ball_tree', 'n_neighbors': 3, 'p': 5, 'weights': 'distance'}                                                                                                  
Bagging                       {'max_features': 1.0, 'max_samples': 100, 'n_estimators': 10, 'random_state': None}                                                                                        
Random Forest                 {'criterion': 'entropy', 'max_features': 1.0, 'min_samples_split': 10, 'n_estimators': 50}                                                                                    
AdaBoost Classifier           {'algorithm': 'SAMME.R', 'learning_rate': 0.5, 'n_estimators': 50, 'random_state': None}                                                                                    
Gradient Boosting Classifier  {'learning_rate': 0.5, 'max_depth': 6, 'min_impurity_decrease': 0.1, 'n_estimators': 10}                                                                                     
XGBoost                       {'booster ': 'gbtree', 'learning_rate': 0.8, 'n_estimators': 1000, 'seed': 0}                                                                                                
