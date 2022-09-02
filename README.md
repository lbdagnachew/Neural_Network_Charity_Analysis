# Neural_Network_Charity_Analysis

## Overview


The purpose of this analyis is to create a a binary classifier that is capable of predicting whether applicants will be successful if funded by a fictional company "Alphabet Soup." The dataset contains over 34,000 organizations that have been funded by alphabet soup. By training a deep learning model on a retrospective dataset of about 34k historical donations, the model served as a binary classifier to predict whether applicants would be successful if given funding. This project is comprised of the following steps:
      -Preprocessing the data for the neural network, 
      -Compile,
      -train and evaluate the model, and
      -optimizing the model
 
##  Resources:

Data Sources: charity_data.csv
Software: Jupyter Notebook,pandas, tensorflow, Visual Studio Code, scikit-learn

## Results 

The column of IS_SUCCESSFUL was used as it contains binary data and was determined to be the target for the model.
The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, AND ASK_AMT were used as the features for the model.
The columns EIN and NAME were determined to have no bearing on the outcome and were removed.      

### Compiling, Training, and Evaluating the Model

Rectified Linear Unit (ReLU) is used as the activation function for both the first and second hidden layers. For the output layer, a sigmoid activation function is used. While training the model, a callback saves the model's weights every 5 epochs. After training, the model's Loss and Accuracy values are evaluated.

###  Summary

The models accuracy ended up being 72.5%.  Although I did not get to the accuracy of 75% that I wanted it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data. 
