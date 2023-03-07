# Neural_Network_Charity_Analysis

## Overview 

In this module we must use a nueral network for decision making. We use a provided dataset to create a binary classifier that will help predict wheather applicants will be succesful if funded by our company, AlphabetSoup. 

## Data Preprocessing

What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?

The target data that we are most interested in for determining which charities to give loans to is likely the IS_SUCCESSFUL data. 
The rest of the data are just features to help train the model. The two variables that are neither targets nor features is the the EIN and NAME columns that wouldn't help the algorithm in anyway. 

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

In my first attempt I used the default inputs of 8 nuerons, 6 layers has the defualt relu fuctions along with a sigmoid function for classification. I was only able to achieve a 73% accuracy. In my subsequent 3 attempts I reduced the thresholds for classifications, removed the status column to help throw out unnecessary data but only achieved a 72% accuracy. I then increased the number of nuerons to 12, while keeping the same features as before achieving 72% accuracy again. Finally I reduced both nuerons and layers to 8 and 4 respectively only to achieve 72% accuracy again. 
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

## Summary

After 3 attempts I was unable to achieve 75% target accuracy. Perhaps machine learning models like random forests or deep learning would be better in getting the accuracy right as they are much more in tune to binary classification and sigmoid functions as described in module 20.5.2. When you have too few features to train the nueral network they become prone to overfitting and can be hard to train. 

