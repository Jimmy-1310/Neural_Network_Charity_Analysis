# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis was to develop a neural network model that could predict if an application for a donation would turn out to be succesfull or not and therefore establish if it was worth to supoport it.

For this project I learned how to create Neural Networks using preceptons and input, hidden and output layers.

## Results

- The target variable in this case is the "IS SUCCESFULL" column. This determines if a campaign is succesful.
- Feature variables: The variables that will be used to determine the output are Application_type, Affiliation, Class, Use_Case, Organization, Income_AMT, Ask_AMT.
- Neither target nor feature: The feature that are discarded are the EIN and Name because they do not bring anything to the analyze aside from identification.

- For the neural network model, 3 layers were used the first one with 80 neurons and the second one with 30 neurons, lastly the output layer had 1 binary output.

![NN_model](https://user-images.githubusercontent.com/95836718/173684746-5342c247-13a8-413c-9f08-d863679d944c.png)

- When trying to improve it, the accuracy was able to increase to a 64% only by reducing the epochs.
- Three attempts were made to improve the accuracy. The first included adding more Neurons, the secund one was adding another hidden layer and lastly, reducing epochs.

## Summary

The outcome of this project is a model that has a decent ammount of accuracy, although some check-up of the predictions might be needed to really see if future outputs are corect. As a recommendation I think the RandomForest model should be tryied to see if the accuracy improves and also check how each feature affects the results.
