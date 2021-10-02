# Object-classification
Created a object classification model on CIFAR-10 dataset using CNN (Convolution Neural Network).
The dataset contains 60,000 images of 10 different kind of objects and the task is to classify those images.

I have trained a CNN with an accuracy of 70% on test data.

Parameters used in training :
    Convolution layers = 2
    Hidden layer = 1
    Activation function = relu (for convolution and hidden layers)
                        = softmax (for output layer)<br>
    Optimizer used = Adam<br>
    Loss = sparse_categorical_crossentropy<br>
    Filter size for convolution layer = 3X3<br>
    Epochs = 10

Libraries used :
    tensorflow
    keras
    numpy
    matplotlib
    sklearn
