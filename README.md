# Neural_Network_Charity_Analysis

## Overview of the analysis:

In this analysis we will be helping the organization Alphabet Soup by creating a deep learning neural network that predicts which organizations are worth donating too and which are to high risk. We will be using the python tensor flow library to achieve this.


## Results: Using bulleted lists and images to support your answers, address the following questions.

What variable(s) are considered the target(s) for your model?
The Is_Successful column is considered the target model

## What variable(s) are considered to be the features for your model?
Application_Type, Affiliation, Classification, Use_Case, Organization, Income_Amt, and Ask_Amt are considered to be features for the model. 


## What variable(s) are neither targets nor features, and should be removed from the input data?
The variables 'EIN', 'Name', Status, Special_Consideration should be removed from the input data. 


![Screen Shot 2022-10-29 at 11 14 25 AM](https://user-images.githubusercontent.com/106411743/198839270-9a167fa1-5c12-4366-a4e3-4b5f2abcc7b7.png)



## How many neurons, layers, and activation functions did you select for your neural network model, and why?

I selected 120 neurons with a sigmoid function for my first layer, 50 nuerons with a ReLU function for the second, and 18 neurons with for the third, and a sigmoid function for the outer layer. I chose to change the activation function for the first layer because it increased the model's performance.

## Were you able to achieve the target model performance?
I only achieved an accuracy of 68% and was not able to achieve the target model performance.


## What steps did you take to try and increase model performance?
I tried to increase the model performance by adding more neurons to the hidden layer, increasing the number of epochs, and by dropping more columns. 

![Screen Shot 2022-10-29 at 11 16 18 AM](https://user-images.githubusercontent.com/106411743/198839339-0b73e590-76e6-4faf-ad99-0d009b5ee0de.png)

## Summary:

Overall, in this model the removal of noisy features, additional neurons, hidden layers, and changed activation functions the accuracy for predicting whether a donation is successful ended up being 0.68 and the loss was 1.05.

I'd recommend a random forest model because it can solve this classification problem by randomly sampling the preprocessed data and building several smaller, simpler decision trees

![Screen Shot 2022-10-29 at 11 17 53 AM](https://user-images.githubusercontent.com/106411743/198839412-102f9cf3-90e4-4bf5-bfa9-5af2d894a30e.png)
