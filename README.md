# CNN-from-scratch
This is the Convolutional Neural Network (CNN) implementation with a single convolution layer from scratch using Numpy library. The image dataset on which classification is done is MNIST. It is able to classify with more than 97% classification accuracy after training for just 1 epoch.

Specifications:

1 convolution layer: 20 filters each of size (5 by 5), stride=1, no padding. It is followed by ReLU activation layer after which max pooling layer of pooling filter size (2 by 2) is added. 
This convolution layer is followed by 3 fully connected layers each containing 2880,100,10 neurons respectively. Sigmoid activation is used for each of these 3 layers. Quadratic loss function is used. 

