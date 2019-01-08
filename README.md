# SY19_Machine_Learning

## Solving 3 problems :
* Regression for the yield_anomaly of a corn farm dataset. Input : **CSV - *2300 rows, 58 predictors***
* Classification for astronomical elements (3 classes). Input : **CSV dataset with *5000 rows, 17 predictors***
* Natural images recognition (3 classes). Input : **JPG** images of different sizes

Best models for now :
* Regression : Random Forest regression (Mean squared error ~= 0.30)
* Classification : SVM with polynomial kernel and C=10 (performance >99%)
* Image recognition : 3 layer neural network, to be replaced with state of the art image network (https://github.com/tensorflow/models/blob/master/research/slim/nets/inception_resnet_v2.py)
