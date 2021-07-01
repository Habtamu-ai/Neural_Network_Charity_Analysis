# Neural_Network_Charity_Analysis
# Overview
The purpose of this project is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.The project uses a data set that contain 34 000 organizations that have received funding from Alphabet Soup over the years to analyse the seccussful organizations.This analysis uses python's TensorFlow library to create, train, and evaluate the data.
# Resources
After carfully observing the data the project established that the target variable is the "IS_SUCCESSFUL" column."EIN" and "NAME" are columns that do not offer any relevant information that could help the model perform better.
The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
Encoding of the categorical variables, spliting into training and testing datasets and standardization have been applied to the features.
 
 ## Compiling, Training, and Evaluating the Model
  - First Attempt, 
This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
The input data has 43 features and 25,724 samples.
The output layer is made of a unique neuron as it is a binary classification.
To speed up the training process, we are using the activation function ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used on the output layer.
For the compilation, the optimizer is adam and the loss function is binary_crossentropy
![Attempt1](https://user-images.githubusercontent.com/78656720/124116402-ec29fe00-da3c-11eb-8c2e-fed399e23595.PNG)


![Attempt2](https://user-images.githubusercontent.com/78656720/124116496-fe0ba100-da3c-11eb-814f-d0f7b4cb0177.PNG)

![Attempt3](https://user-images.githubusercontent.com/78656720/124116508-01069180-da3d-11eb-833a-70f3f11be238.PNG)


# Summary
