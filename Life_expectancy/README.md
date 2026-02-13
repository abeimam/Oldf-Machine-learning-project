Life Expectancy dataset isused in which all the regression models : Multiple Linear Regression, Polynomial Linear Regression, Decision Tree, Random forest and support vector regression 
is implemented.
Preprocessing tasks like: Checking and handling of missing values, featurescaling is done. 
however feature scaling is only necessary in SVR model.

Perfromance evaluation metrics: r2 score is used. 
out of all the models whoose r2 score is maximum is taken for the selection of the model. 

In this case Random Forest got the maximum r2 score and is selected as the main model for implementataion purpose.

Techniques like k fold corss validation and grid search is used on Random Forest.

k fold cross validation: is the robust way of evaluation the performance of a model. in which the different variation of the training and test dataset is chosen 
which reduces the chances of getting the similar kind of test dataset to the training sets and reduced and as a output or final result the average of all the accuracy score 
is considered as final accuracy for the evaluation of the model. 

grid search: technique to find the best hyperparameters for a particular model.
