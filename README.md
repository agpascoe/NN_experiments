# NN_experiments
Some Neural Networks experiments

This bucket is about Neural Network experiments that have been built along several years.

**Pytorch/EMNIST47Pytorch** is a Multiclass classification model using EMINST data set with 47 classes (letters, numbers) https://pytorch.org/vision/main/generated/torchvision.datasets.EMNIST.html. 

**Pytorch/WINE_Correlation_ResidualSugar.ipynb** This model is a correlation predictor that uses the wine dataset of: "https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv". Itcontains a fully class construction for the NN and a parametrized experiment.

**Pytorch/Desease-BiClass-Model** This is a Bi Classification Model, where we need to predict if a pascient with some caharacteristics, might be a heart desease (1) or not. You can find the data set here: 'https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data'.
Nevertheless this is a typical NN problem, the key value of this implementation is in the class encapsulation (the whole model in modeled as a class), the split function, and finally the experiment that runs a bunch of parmeters and a find-the-best-of-bread playing
