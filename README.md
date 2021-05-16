# Kaggle Repository
Repository for your personal Kaggle projects


The code shown here is my submission for the "Titanic" competition on Kaggle. Descriptive data from 1309 titanic passengers was divided into training and test data. I was then tasked with training a model on the "train.csv" data to determine a model that could predict which passengers would survive the sinking of the titanic based on their characteristics(Age, Siblings, Class, Gender etc.). A random forest model with a depth of 8 and nodesize of 3 was developed which could predict this reasonably well(76.55% accuracy for predicting survival). This model was then tuned to determine the optimal nodesize and depth of the random forest. It was found that a random forest model with a depth of 400 and nodesize 4 produced the lowest OOB(Out Of Bag Error). When the new model was tested, there was a slight improvement in predictive power over the test set(77.75% accuracy)   
