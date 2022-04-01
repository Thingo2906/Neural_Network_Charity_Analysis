# Neural_Network_Charity_Analysis
## Overview:
- The goal of this project is to examine and categorize the success of philanthropic donations using deep-learning neural networks and the TensorFlow framework in Python.
 
 We use the following methods for the analysis:
- preprocessing the data for the neural network model,
- compile, train and evaluate the model,
- optimize the model.
## Results:
### Data Preprocessing
- The EIN and NAME columns have been removed since they bring no value to the machine learning model.
- APPLICATION TYPE has been binned, and the unique value with fewer than 500 entries has been grouped as OTHER.
- The binary data in the IS SUCCESSFUL column indicates whether or not the charitable gift was utilised properly. The goal variable for our deep learning neural network is then this variable.
- Added the remaining 43 variables as features.
### Compiling, Training, and Evaluating the Model
- Through two hidden layers and a single output layer, our model generated 5981 parameters from 43 inputs.
- The model's accuracy is less than 75%. This is an unsatisfactory result in terms of predicting the outcome of charitable donations. With a little more time and testing out other optimization profiles we may be able to achieve such accuracy.
## Summary:
- The deep learning neural network model could not achieve the goal accuracy of 75%. Given that this goal level is rather typical, we may conclude that the model is not outperforming.
- We might use a supervised machine learning model like the Random Forest Classifier to combine a number of decision trees to get a categorized output and compare its performance to our deep learning model because we are in a binary classification situation.
