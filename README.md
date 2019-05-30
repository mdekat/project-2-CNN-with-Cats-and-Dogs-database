# project-2-CNN-with-Cats-and-Dogs-database

Convolutional Neural Network

The dataset that is used is the Cats and Dogs dataset from the 2013 Kaggle Competition. It can be found here: https://www.kaggle.com/c/dogs-vs-cats/data.
As mentioned by Jason Brownlee on his website (see bottom of this readme) a simple model does barely exceed 80% accuracy. 

I implemented EarlyStopping  overfitting models (EarlyStopping on Loss). 
I tryed to combinations of BatchNormalization and/or DropOut to see what the effects are on learning. Results can be foundin the Notebook file.   

## The notebook file contains the following steps:
0. import libaries
1. load and prep data
2. create and compile model
3. train model
4. evaluate model

## Results
Results can be found on the bottom of the Notebook file. Accuracy gets stuck at around 80% in all the models.
Batch Normalization increases the stochastic nature of the earning of the model (as expected).
Dropout reduces overfitting (as expected).

In this case the use of Dropout was a necessity. 

## Many thanks to Jason Brownlee:
https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-photos-of-dogs-and-cats/
