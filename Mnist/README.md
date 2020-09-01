# Mnist
An ML model based on Sgd/Random forest classifier that classifies Handwritten digits.

Sci-kit learn  earlier used to download dataset from mldata.org which was shutdown. After the 0.20 update alternative approach emerged for downlaodin the dataset fetch_openml().
The fetch_mldata() used to fetch two datasets one of instances and other of corresponding targets, while the structure of the data hasn't changed with the change of method.But the targets earlier stored 8-bit unsigned integers which have now been replaced by strings
Also , the dataset from prior method was sorted whereas the dataset now is unsorted.
