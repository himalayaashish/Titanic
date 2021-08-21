# Titanic 

 	   model 	                best_score 	                              best_params
0 	LogisticRegression 	    0.794614 	                            {'C': 1, 'penalty': 'l2'}
1 	DecisionTreeClassifier 	0.772205 	                            {'criterion': 'gini'}
2 	KNeighborsClassifier 	  0.813697 	                            {'n_neighbors': 20}
3 	SVC 	                  0.828278 	                            {'C': 5, 'kernel': 'rbf'}
4 	random_forest 	        0.811462 	                            {'n_estimators': 2000}
5 	AdaBoostClassifier 	    0.796905 	                            {'learning_rate': 0.1, 'n_estimators': 100}
6 	**XGBClassifier** 	        0.844015 	                            {'colsample_bytree': 1.0, 'gamma': 1, 'max_dep...
7 	lgb 	                  0.644253 	                            {'boosting_type': 'gbdt', 'colsample_bytree': ...
