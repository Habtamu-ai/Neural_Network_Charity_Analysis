# Neural_Network_Charity_Analysis
# Overview
The purpose of this project is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.The project uses a data set that contain 34 000 organizations that have received funding from Alphabet Soup over the years to analyse the seccussful organizations.This analysis uses python's TensorFlow library to create, train, and evaluate the data.
# Resources
After carfully observing the data the project established that the target variable is the "IS_SUCCESSFUL" column."EIN" and "NAME" are columns that do not offer any relevant information that could help the model perform better.The project usses the remaining columns as the features for the model.
 -First attempt
For my first attempt at compiling a neuron network consisted of 8 neurons in the first layer and 6 in the second. Both layers had relu activation functions and the output layer had a sigmoid activation function. I started with these parameters as relu does better with nonlinear data, and two layers allows for a second layer to reweight the inputs from the first layer. Here are the preformance metrics of this model.
# Summary
