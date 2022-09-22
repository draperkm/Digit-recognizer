# CNN for digit recognition

This is a Classification problem. The netwrok will try to predict the true label attached to the input image with which it is feeded. The dataset used was the [MNIST](http://yann.lecun.com/exdb/mnist/) and we reached an accuracy of 99.33%.

## About the data set used
The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/MNIST.png" width="600" height="325">


## Architecture

The netwrok is composed by 4 convolutional layers. The first two convolutional layers are composed by 28 nodes each, while the last two by 14 nodes each. In between these layer we make use of the maxpooling and dropout operations. After this layers group, the output gets flattened out, and three fully connected layers for the final classification network. The final fully connected layer is made of 10 nodes, each one corresponding to a digit from 0 to 9. Below we can see two representations of the same network. 

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/Screenshot%202022-07-06%20at%2020.52.57.png" width="600" height="250">

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/Screenshot%202022-07-06%20at%2020.08.48.png" width="400" height="500">


## Imported libraries (Keras implementation)

Pandas 

Numpy

Matplotlib

Sklearn

Keras

Tensorflow

