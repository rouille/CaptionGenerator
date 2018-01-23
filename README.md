# Caption Generator
The goal of this project is to develop a deep learning model capable of automatically generate a caption for photographs. Note that methods from both computer vision and natural language processing in order to turn the understanding of the image into words in the right order.

## Dataset
The Flickr8K dataset is used. You will need to first fill out a request form (the form is available [here](https://forms.illinois.edu/sec/1713398)) prior to downloading the dataset. The images will then be pre-processed before being fed to the deep learning model.

## Deep Learning Model
The Keras library is used as a deep learning framework and transfer learning techniques are applied to build the model. Keras provides state-of-the-art deep learning models that have been previously trained on large dataset such as [ImageNet](http://www.image-net.org/). The VGG16 deep learning model, the winner of the 2014 ImageNet Large Scale Visual Recognition Competition, is chosen for this project. Such model captures universal features in its early layers that are relevant and useful to most computer vision problems, and, consequently, leveraging such features allow to reach a better accuracy than any method that would only rely on the available data.
