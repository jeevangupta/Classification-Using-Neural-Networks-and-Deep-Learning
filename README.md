# Classification Using Neural Networks and Deep Learning

   **In this project, you are required to understand the whole process of compiling different layers (Convolutional Layer, Fully-Connected Layer, Pooling Layer, Activation Layer, Loss function) of a simple Convolutional Neural Network (CNN) for the visual classification task. And you need to compile your own evaluation code to evaluate the trained CNN to obtain the training and testing results.**

## Description 

   In this part, we will revisit the Handwritten Digits Recognition task in Part 1, using a convolutional neural network. The basic dataset is the same MNIST dataset from Part I, but you may choose to use only a subset for training and testing, if speed performance with the entire dataset becomes a bottleneck. For example, you may use only 6000 samples for training (each digit with 600 samples) and 1000 samples for testing (each digit with 100 samples).

   The basic requirement of this part is to experiment with a convolutional neural network with the following parameter settings:

   1. The input size is the size of the image (28x28).
   2. The first hidden layer is a convolutional layer, with 6 feature maps. The convolution kernels are of 3x3 in size. Use stride 1 for convolution.
   3. The convolutional layer is followed by a max pooling layer. The pooling is 2x2 with stride 1.
   4. After max pooling, the layer is connected to the next convolutional layer, with 16 feature maps. The convolution kernels are of 3x3 in size. Use stride 1 for convolution.
   5. The second convolutional layer is followed by a max pooling layer. The pooling is 2x2 with stride 1.
   6. After max pooling, the layer is fully connected to the next hidden layer with 120 nodes and relu as the activation function.
   7. The fully connected layer is followed by another fully connected layer with 84 nodes and relu as the activation function, then connected to a softmax layer with 10 output nodes (corresponding to the 10 classes).

   We will train such a network with the training set and then test it on the testing set.

   You are required to plot the training error and the testing error as a function of the learning epochs. You are also required to change some of the hyper-parameters (the kernel size, the number of feature maps, etc), and then repeat the experiment and plot training and testing errors under the new setting.

   These are the minimum requirements. Additional requirements may be added (like experimenting with different kernel sizes, number of feature maps, ways of doing pooling, or even introducing drop-out in training, etc.).
