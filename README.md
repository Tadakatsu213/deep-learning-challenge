# deep-learning-challenge
Summary
The goal of this project was to build a model to help Alphabet Soup predict which funding applicants are likely to succeed. We used historical data and created a binary classifier to make these predictions.

Key Steps:
Data Preprocessing:

We removed unnecessary columns (EIN and NAME).
Rare categories in APPLICATION_TYPE and CLASSIFICATION were grouped into "Other."
Categorical data was converted to numbers using one-hot encoding.
We scaled the data using StandardScaler to prepare it for modeling.
Initial Model:

We built a neural network with two hidden layers:
First layer: 80 neurons, ReLU activation.
Second layer: 30 neurons, ReLU activation.
The output layer used a sigmoid function for binary classification.
We trained the model for 100 epochs using the adam optimizer.
Optimized Model:

To improve the model, we made several changes:
Added a third hidden layer.
Increased the number of neurons and changed activation functions (ReLU and tanh).
Switched to the adamax optimizer.
Increased the number of epochs to 200.
The optimized model was saved as AlphabetSoupCharity_Optimisation.h5.
