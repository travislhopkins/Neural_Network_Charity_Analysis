# Neural_Network_Charity_Analysis
Module 3 challenge

PURPOSE

The purpose of this analysis is to predict what applications for funding should be approved (or not) by Alphabet Soup's business team. Alphabet Soup would like to reduce risk associated with companies misusing funds. 

METHOD

A dataset of 34,000 organizations that have received funding from Alphabet Soup was used to train an artificial neural network model.

RESULTS

Several optimization techniques were used but the best accuracy rate achieved was 73%.
The preprocessing identified the columns as labeled below:
	
	• EIN and NAME—not used in model
	• APPLICATION_TYPE—feature
	• AFFILIATION—feature
	• CLASSIFICATION—feature
	• USE_CASE—feature
	• ORGANIZATION—feature
	• STATUS—feature
	• INCOME_AMT—feature
	• SPECIAL_CONSIDERATIONS—feature
	• ASK_AMT—feature
	• IS_SUCCESSFUL— target of the model

The initial model had two hidden layers and an output layer.

	• Input layer
	• Hidden layer 1 - 80 neurons; activation: relu
	• Hidden layer 2 - 30 neurons; activation: relu
	• Output layer - 1 neuron; activation: sigmoid

I was not able to achieve the target model performance. I tried increasing the number of hidden layers by one layer, changing the activation functions of the hidden layers to tanh, and increasing the training epochs to from 100 to 200 to 500. 
