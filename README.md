# neural_net
# Building a simple convolution network
------------------------------
#Importing libraries and dataset

import tensorflow
import dataset
train/test split
Reshape & normalize train & test images
------------------------------
#Defining model

Sequential model
1 convolutional layer
1 Max Pooling
2 convolutional layer
2 Max Pooling
Flatten Layer
Dense Layer(relu)
Dense layer(softmax)
-------------------------------
#Compile, Train, Evaluate

Comiple Model(optimizer, loss, matrics)
Train/Fit(train_i, train_l, epochs)
Evaluate(test_i, test_l)
Print('test loss', 'test accuracy')
