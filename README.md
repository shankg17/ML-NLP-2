# ML-NLP-2

###  Classification

 In this exercise, We will practice classification problem using logistic regression, LDA and KNN methods, and compare the model using out of sample data, base on confusion matrix.
 
 Data: use iris data, 2-dimension with predictors Petal Length and Petal Width, Species only includes setosa and versicolor.
 
 1. Use 70% randomly picked observations as training data, train the logistic regression, LDA and KNN(3).
    
 3. The30%heldoutdataused to test against the models. Compare model performance based on confusion matrix for each model, and print out of sample error rate.
    
 ### Tree Method
 
 Use Carseats dataset in ISLR library. Predict Sales level based on other predictors in the dataset.
 
 1. Convert Sales into qualitative variable SalesGrp with four groups base on quartiles. Fit a classification tree, plot the tree, and interpret the results, what is the MSE?
 
 2. Use cross-validation in order to determine the optimal level of tree complexity(cp). Does pruning the tree improve the test MSE?

 ### Resampling Methods
 
 Use income, balance and dummy variable student to predict whether default in the Default data set(in ISLR library).
 
 Estimate the test error of this logistic regression model using the validation set approach. Comment on whether or not including a dummy variable for student leads to a reduction in the test error rate.
