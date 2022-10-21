# Neural_Network_Charity_Analysis

# Overview of the Analysis

The objective of this analysis was to assist Alphabet Soup in their investment. We have used machine learning and neural network on the dataset provided to predict whether an applicant funded by Alphabet Soup will be successful.  

# Results
## Data Preprocesing

1. What variable(s) were considered the target(s) for your model?
Those entities that have been successfully funded by Alphabet Soup were considered as target for our analysis

2. What variable(s) were considered to be the features for your model?
Entities listed in the IS_SUCCESSFUL column were treated as features for our model

3. What variable(s) are neither targets nor features and should be removed from the input data? 
We dropped the EIN and NAME columns from the input data as these were not beneficial to the model.

## Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why? 
I have used 2 layers, the first layer uses 80 neuron and has an 'sigmoid' acitvation function. The second layer uses 30 neuron and has a 'relu' activation function. This gives me an accuracy of 72.1% 

2. Were you able to achieve the target model performance?
No, I was unable to reach the target goal of 75% for accuracy. 

3. What steps did you take to try and increase model performance? 
I have tried several different approaches to improve model performance. I have added more layer (upto 4) and changed the number of neurons (both increased and decreased), keeping the number of neurons in the first layer always higher than the sum total of all other layers. I have also tried different permutations of activation functions for these layers. All these changes did not change the accuracy appreciably, with the highest being ~72.6. Unfortunately, I did not save that code to document it. Other changes were downright deterimental with accuracy dropping as low as 42%.  

# Summary
We have created a machine learning model to assist Alphabet Soup make decisions on their investments. Based on the current data the best accuracy of 72.1% was obtained by using the relu and sigmoid functions. Other activation functions and changes in number of neurons were tried with marginal success. With this being the simplest model, one could try using other classifers. The dataset can also be reprocessed to omit certian outliers beforehand that could improve the accuracy of the model.
