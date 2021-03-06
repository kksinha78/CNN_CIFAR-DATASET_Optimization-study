# CNN_CIFAR-DATASET_Optimization-study
CIFAR-10  is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class
A study of CNN model performace by using different optimization techniues like dropouts,L2 regularization, Batch normilaization, No of layers etc

Some hyperparameters we will play with are:

Adding and removing dropouts in convolutional layers

Batch Normalization (BN)

L2 regularisation

Increasing the number of convolution layers

Increasing the number of filters in certain layers 

Conclusion : Based on these experiments, we saw that the performance of CNNs depends heavily on multiple hyperparameters - the number of layers, number of feature maps in each layer, the use of dropouts, batch normalisation, etc. Thus, it is advisable to first fine-tune your model hyperparameters by conducting lots of experiments. Only when you are convinced that you have found the right set of hyperparameters you should train the model with a larger number of epochs (since almost always the amount of time and computing power you have is limited)
