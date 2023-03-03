# Neural Network Charity Analysis

## Overview
Use features in a dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alpahabet Soup. Backed up with historical data from its 34,000 organizations that have received funding.

## Results

Some consideretions to get the data ready:

- The target values will be the consideration if the money was used effectively, denoted by column 'IS_SUCCESSFUL'.

- All the variables considered from this data to be features are all the categorical and numerical data.

- Names and identification columns will be discarded as they don't provide useful information for analysis.

Model selection and evaluation: 

- As the number of features resulted in 43, the choice of input layers was decided to be almost doubled to 80. Three layers were considered enough and activation functions were selected with a first strong approach with rectified linear unit and transitioned with a hyperbolic tangent one to end up with a sigmoid binary selection.

- Model achived 72.2% Accuracy while evaluated with test data. 

- To increase model performance 3 methods were chosen: Add more hidden layers, Increasing the epochs to the training and adding more neurons to the layers.

## Summary 

None of the modifications were enough to improve considerably the model performance and it's recommended another approach to obtain better results. Recurring to neural networks didn't seem to help with this particular dataset and would rather try with an Easy Ensemble Classifier to compare outcomes.
