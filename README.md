# Image Identification Model for identifying Bird Species

This project uses a CNN to identify the species of bird by passing its image as input.

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) 
to various aspects/objects in the image and be able to differentiate one from the other.

The CNN model is implemented **Tensorflow with Keras**.

The model was made by fine-tuning the MobileNet model (https://arxiv.org/abs/1704.04861) over a dataset of around 17,000 images.
The dataset used was 300 Bird Species - Classification (https://www.kaggle.com/gpiosenka/100-bird-species/metadata)
