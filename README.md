# Deep Learning Object Recognition in Photographs using CIFAR-10 dataset

This project aims to recognize objects in photographs using deep learning techniques with the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Getting Started
To get started with this project, you will need to have Python 3 and the following libraries installed:

TensorFlow: Keras is now integrated into TensorFlow 2.0+, meaning that when you install TensorFlow 2.0+, Keras is automatically installed as well. This integration allows for a seamless user experience and makes it easier to build and train neural networks using the Keras API. With TensorFlow 2.0+, you can use the tf.keras module to define and train your neural network models using Keras.



## Dataset
You can download the CIFAR-10 dataset from the following link: https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz. The dataset is divided into five batches, stored in the cifar-10-batches-py folder.

## Model
We use a convolutional neural network (CNN) model to recognize objects in photographs. The model consists of several convolutional layers, flatten layers, pooling layers, and fully connected layers.

## Results
Our CNN model achieved an accuracy of 67.60% for simple CNN model and  80.34% for large CNN model on the CIFAR-10 test dataset. See the python codes and outputs for details.

## Conclusion
In conclusion, this project demonstrates how to use deep learning techniques with the CIFAR-10 dataset to recognize objects in photographs. With some fine-tuning, the model can achieve even better accuracy.




