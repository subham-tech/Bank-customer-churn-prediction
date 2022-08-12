# Bank-customer-churn-prediction
An Artificial Neural Network(ANN) classifier model.

### This prediction software will help banking institutions to keep a tab on the customers who have a high probability of churning out from their services so that they can come up with ways to retain them.

The code is basically divided into four parts.

* In the first part, we import the libraries, dataset and preprocess the data where we encode all the categorical data then we split our dataset into training and test set and apply feature scaling. For neural network models feature scaling is mandatory.

* In the second part, we build an artificial neural network or ANN for which first we initialise a sequential model then add 2 dense hidden layers and then we add another dense layer which acts as an output layer.

* In part 3,  we compile the ANN model by using adam optimizer after that we train the model with a batch size of 32 for 100 epochs.

* In the last part, we make predictions and evaluate our model by plotting the confusion matrix and calculate the accuracy score.
