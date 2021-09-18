# Image Identification Model for identifying Bird Species

This project uses a CNN to identify the species of bird by passing its image as input.

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) 
to various aspects/objects in the image and be able to differentiate one from the other.

The CNN model is implemented using **[Tensorflow with Keras](https://www.tensorflow.org/)
**.

The model was made by fine-tuning the MobileNet model (https://arxiv.org/abs/1704.04861) over a dataset of around 17,000 images. \
The dataset was split into training, validation, and testing sets in an 80:10:10 ratio. 80% images (14095) images were used for training, 10% (1677) images were used for validation and 10% (1695) images were used for testing. \

The dataset used was 300 Bird Species - Classification (https://www.kaggle.com/gpiosenka/100-bird-species/metadata)

![image](https://user-images.githubusercontent.com/63246596/133881604-a17e4339-a558-4a4a-bde6-0cc1d6e2adba.png) \
Fig. (Random sample of training data) 

![image](https://user-images.githubusercontent.com/63246596/133881624-940bf876-5539-4567-af3c-59c15130238d.png) \
Fig. (Random sample of validation data) 

![image](https://user-images.githubusercontent.com/63246596/133881630-8a671dd7-888f-4eca-955b-429fd365fb2a.png) \
Fig. (Random sample of testing data)

## Testing Accuracy

The accuracy was calculated by checking if the predicted labels match the actual labels or not. The model got an accuracy of 93.63% on the test set which contained 1695 images. \
![image](https://user-images.githubusercontent.com/63246596/133881659-26474904-14e2-47d3-b684-d391a8181c2b.png)

**Training Loss and Validation Loss over epochs** – \
![image](https://user-images.githubusercontent.com/63246596/133881669-fb078476-bbc2-48a1-992b-886c70b439ae.png) 

**Training Accuracy and Validation Accuracy over epochs** – \
![image](https://user-images.githubusercontent.com/63246596/133881691-2d398eff-3bdf-4df7-b99c-f0476750b2ed.png)
