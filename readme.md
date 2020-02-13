# Overview

A convolutional neural network for German traffic sign image classification.  

# Dataset 

[Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) is an image classification dataset. It was made available in 2011 as part of a competition at the International Joint Conference on Neural Networks (IJCNN). The dataset contains  43 classes and over 50,000 images in total. 

Note: the dataset was not uploaded in this repository.

# Model
A convolution neural network having the following architecture:

`CONV2D -> MAXPOOL -> DROPOUT -> CONV2D -> MAXPOOL -> DROPOUT --> FLATTEN -> FULLYCONNECTED -> DROPOUT -> FULLYCONNECTED`

It was trained from scratch on the training data using [PyTorch](http://pytorch.org/).

# Metrics

The model achieved xx% accuracy on the validation set (random 20% subset of the training dataset).