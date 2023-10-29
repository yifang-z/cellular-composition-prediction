# cellular-composition-prediction
This code is to develop a regression model for predicting the number of six different types of cells in a given histological image patch.

In this project, the data from the CoNIC: Colon Nuclei Identification and Counting Challenge (see: https://github.com/TissueImageAnalytics/CoNIC). The whole data analysis steps are covered in this project, data cleaning, data pre-processing with H-channel, pic feature extraction, classical regression with Ordinary Least Squares (OLS) regression, Support Vector Regression and Multilayer Perceptron (MLP), in the end convolutional neural network (in PyTorch) are used to predict the counts of 6 types of cells simultaneously given the image patch as input and perform 3-fold cross-validation using the given folds.

All the codes and explaination in ipynb file, using google colab to open and run.

