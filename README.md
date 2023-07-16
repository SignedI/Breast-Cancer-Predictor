# Breast-Cancer-Predictor
This is a very simple model that predicts whether a tumor is malignant or benign, using the computed features of the digitized image of the breast mass.

The model employs the use of Support Vector Classifier(SVC) and Support Vector Machine(SVM) to predict the onset of cancer by reading the features provided. This project also aims to find the better model of the two.

SVC is a linear classifier whereas SVM is generally a non-linear classifier, and uses what we call as a 'kernel trick' to classify the data non-linearly. In our model, we use Radial Basis Function Kernel (RBF).

Although being non-linear makes it bit a less efficient, the accuracy of the SVM model is generally higher than the SVC.
