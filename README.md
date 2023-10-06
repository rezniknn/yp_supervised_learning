This repository contains one of the projects completed as part of the Data Science+ Yandex Praktikum course. 

In this work, we applied three classes of machine learning models to the problem of classifying bank customers to predict their churn. The best accuracy of 61% according to the F1-score metric was shown by the decision tree model. The best model hyperparameters: max_depth=12 n_estimators=32. The model's initial accuracy of 58% was increased by balancing the classes in the source data using upsampling. 

Analysis of the ROC curve and calculation of the AUC-ROC metric confirmed the quality of the trained model; the model showed a value of 0.84 according to the AUC-ROC metric on the test data. 
