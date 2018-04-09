## Introduction
In this project we have developed deep learning model to recognise hand written digits.

### MNIST Dataset
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. These images were normalized in size and centered. Each image is in a 28x28 square (784 pixels). 60,000 images were used to train a model and 10,000 were used to test it.

## Multilayer Perceptrons Model:-
We have converted the 28*28 pixel into 2d vector and forwarded the 2d vector to input layer. We then change the grayscale values from 0-255 to 0-1 to make things easier on our neural network. (Normalization). Our current neural network structure is as follows:

Visible Layer (784 Inputs) >> Hidden Layer (784 Neurons) >> Output Layer (10 Outputs).

We can increase or reduce number of hidden layers with different activation such as Relu, Sigmoid and Softmax. We have used model.fit() python liberary to train the data and model.evaluate() for the evalution.

## Conclusion:-
We have tired all the combination of activation function and we found that our accuracy is around 98% and Relu-Softmax combination  has given the min error rate.
