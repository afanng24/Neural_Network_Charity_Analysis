# Neural Network Charity Analysis

## Overview of Project
The objective of Neural Network Charity Analysis is to use the provided dataset named “charity_data.csv” and figure out a way to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. To accomplish this task, we must consider which variables are considered the targets for our model, what variables are considered to be the features for our model, and what variables are neither ratgets nor features and to remove them. After the model is complete we will refactor our code to increase performance by creating more hidden layers, adding more neurons to the hidden layers and adding epochs to the training regimen. 

## Resources
**Source of Data** : charity_data.csv

**Software** : Python, Pandas, Jupyter Notebook,

## Results
- The variable that should be considered as the target is the "IS_SUCESSFUL"
- The variables considered to be features for the model are underlined as the varying column names. Such as Status, Application_Type, Affiliation, Classifications, Use_Case, Organization, Income_Amount ,and  Special_Considerations.
- The variables of “Ein” and “Name” are neither targets nor features, and were removed early on in the code. 

### Compling, training and evaluating the model

- The number of input features was 43 because that is the amount of columns in the dataset after Name and Ein have been dropped as well as the additional columns from the various Income_Amount, and Affiliation columns which have ranges after them. The first hidden node layer has 80 neurons and the second hidden node layer has 30 neurons. 
- The target accuracy for the first iteration of the model averaged to 67% accuracy so the target model performance was not reached.
- The model was optimized to achieve a higher target model accuracy by increasing the hidden node layers from 2 to 5, the first two layers were increased from 80 and 30 to 100 and 50, the activation function for the hidden layers were also changed from relu
to tanh.The save frequency was changed to every 5 seconds and the epochs was changed from 100 to 200 for a larger sample size. 

## Summary
