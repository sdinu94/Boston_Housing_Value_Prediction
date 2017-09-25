# Boston Housing Value Prediction

# Dataset

The dataset used is Boston House Price dataset. 

The dataset is available at: https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data

The dataset has 14 columns on data. It describes 13 numerical properties of houses in Boston suburbs and is concerned with modeling the price of houses in those suburbs in thousands of dollars. Input attributes include things like crime rate, proportion of nonretail business acres, chemical concentrations and more. 

The description about the attributes are available at: http://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

# Approach

This is a regression predictive modeling problem. Deep learning algorithm like Neural Network was used to predict the output. The project was implemented in Python. Keras package was widely used in modeling. Other packages like Scikit, Numpy and Sklearn were used. Before coming up with the final model, the hyper parameters like number of neurons, activation function, optimizer algorithm and lot more were identified by Grid Search. This is done to get the best possible model with minimal error. The model was evaluted by 10-fold cross validation and obtained a MSE of 20 in square thousands of dollars. 
