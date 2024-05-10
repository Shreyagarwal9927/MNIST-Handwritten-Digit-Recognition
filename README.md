# MNIST-Handwritten-Digit-Recognition
This repository contains code meant to classify MNIST Handwritten Digits using Neural Networks.
I have imported the mnist dataset from keras using "from keras.datasets import mnist".
There are 3 code files described below:-

"app.py" code sets up a Pygame window with a canvas for drawing. When the user draws a digit on the canvas, the code recognizes the digit using a simple digit recognition model (replace this with your own model). The recognized digit is then displayed on the screen.

"bestmodel.h5"code snippet to save the best model only of handwritten digit recognition using the bestmodel.h5 file.

"mnist_train.ipynb" is a jupyter source file, this code will load the MNIST dataset, preprocess the data, define the model architecture, compile the model, and train the model. The best model will be saved to the bestmodel.h5 file.
It also incorporates a couple of convolutional layers and a softmax output layer in addition to fully connected layers. Dropout has also been implemented in fully connected layers to address the problem of overfitting.

The best efficiency I obtained was 99.08% with a couple of convolutional layers and an output softmax layer of 10 neurons. The network trained over 50 epochs, and took a long while.
