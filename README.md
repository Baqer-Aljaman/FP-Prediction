# A comprehensive neural network model for predicting flash point of oxygenated fuels using a functional group approach

## Abstract

In the present work, artificial neural network (ANN) has been used for developing a comprehensive model for predicting flash point (FP) of petroleum fuels containing the following oxygenated chemical classes: alcohols, ethers, aldehydes, ketones and esters. 474 pure compounds and 314 blends comprising of various compounds were used for model development. The fuels were dissembled into eleven constituent functional groups namely, paraffinic CH3, CH2 and CH groups, olefinic -CH=CH2 groups, naphthenic -CH-CH2, aromatic C-CH groups, alcoholic OH groups, ether O groups, aldehydic CHO groups, ketonic CO groups and ester COO groups. These eleven groups were treated as model inputs along with molecular weight (MW) and branching index (BI) which is a structural parameter. These 13 inputs were calculated for each of the 788 fuels to generate a dataset, which was used to train the model. Two ANN models were developed, one using Matlab and other using Keras, an interface for ANN library. GridSearchCV and RandomSearch were used to optimize the network in the Keras model. The developed models showed satisfactory results when applied against the entries in the test set which comprised 20% of the dataset that was not used for model training.  The regression coefficient for the comparison between the experimental and predicted data was found to be 0.981 (Matlab model) and 0.979 (Keras model). The developed models have low mean absolute errors of 3.12 K (Matlab model) and 3.55 K (Keras model) and can be used to predict (and screen) FP’s of various complex oxygenated compounds and their mixtures.

## For testing the developed model
1) Download the files:
        a) Flash Point Model Deployment (KM).ipynb
        b) FP_developed_KM
2) Open file (a) and follow the comments inside the code
