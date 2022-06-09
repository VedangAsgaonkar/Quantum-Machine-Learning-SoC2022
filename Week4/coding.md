# Coding Tasks
All these tasks must be implemented in seperate jupyter notebooks. You may want to have a basic idea of [numpy](https://www.tutorialspoint.com/numpy/numpy_introduction.htm) and [pandas](https://www.tutorialspoint.com/python_pandas/python_pandas_introduction.htm). It is recommended to study at least a subset of the resources given for numpy and pandas above. 
## Linear regression
Use [sklearn](https://scikit-learn.org/stable/) to carry out linear regression on this [weather dataset](https://www.kaggle.com/datasets/budincsevity/szeged-weather). First regress humidity against temperature and then try and perform a multi-variable linear regression of humidity against temperature and pressure.
## Clustering
Perform k-means clustering on the famous [iris flower dataset](https://www.kaggle.com/datasets/uciml/iris) using [sklearn](https://scikit-learn.org/stable/). Cluster the data in a multi-dimensional space of features like sepal length, width, petal length and width. How well does the clustering perform with respect to the original labels of the dataset?
## Support Vector Machine
Perform SVM classification on the [breast cancer dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?resource=download). Choose a subset of the features that you find appropriate and perform SVM classification using [sklearn](https://scikit-learn.org/stable/) into malignant and benign.

## Neural networks
We will use [tensorflow](https://www.tensorflow.org/resources/learn-ml?gclid=CjwKCAjwtIaVBhBkEiwAsr7-c5UYPeuDufMzL1dZkf5JtVK1eVK-3X7u4Nv-1h3o_Gb3GrvNA1F7-BoCssUQAvD_BwE) to implement some basic neural networks. You can look up [ML basics with Keras](https://www.tensorflow.org/tutorials/keras/classification) section. You can try some of the notebooks from there. You need to submit a neural network which classifies images from the MNIST dataset into 10 categories (the 10 single digit numbers).

## Submission
In totality, you need to submit 4 .ipynb files, one for linear regression for weather, one for clustering for iris flower classification, one for SVM for breast cancer classification and the last for NN for MNIST classification. 