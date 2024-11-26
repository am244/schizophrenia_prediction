# Prediction of patients with schizophrenia from anatomical brain imaging 

This repo contains the Applied AI coursework to predict whether patients have schizophrenia on the basis of MRI scans.  A logistic regression model with elastic net regularisation, light gradient boosting machine (LightGBM), and support vector machine (SVM) with a radial basis function (RBF) kernel were compared. These models were applied to both a low and high-dimensional version of pre-processed structural MRI data.  Two cross-validation strategies were also bechmarked: a common cross-validation strategy and group stratified cross-validation by sex.  The relatively simple logistic regression model performed at least as well, if not better, than the other models on the test set in all scenarios.

The Jupyter notebook (`.ipynb`) and report pdf file are provided. This coursework used the RAMP challenge environment, with the pre-provided code and description integrated into the Jupyter notebook.  
