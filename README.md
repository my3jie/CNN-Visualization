# CNN-Visualization
This repository contains a basic visualization of all convolutional layers of a small CNN.

For this task i have trained a small Convolutional Neural Network for binary classification of cat Vs Non-cat on a small dataset of 209 training images and 50 test images

The structure of the model is as follows:-

(Note:- these optimised hyper parameters have been obtained after testing many combinations)

Input Layer:-209 Training images of size 64X64 across 3 RGB channels

CONVOLUTIONAL LAYERS

1st convolutional Layer:- this layer has 16 5X5 filters with SAME padding(padding of 2) and a stride of 1. and is RELU activated

1st Pooling Layer:- this is a Max-Pooling Layer with 2X2 filter and a stride of 2

2nd Convolutional Layer:- This layer has 16 filters each of size 5X5 , having SAME padding(padding of 2) and a stride of 1. And later is RELU activated.

2nd Pooling layer:- This layer has Max-Pooling with filter size of 2 and a stride of 2

FULLY CONNECTED LAYERS

Hidden units:- The flattened outputs are fed into one hidden layer with 64 neurons, which are RELU activated

Output Layer:- The FInal layer has 1 single neuron which is Sigmoid Activated and produces a prediction value between 0 and 1

The complete code and visualization can be found in the .ipynb file above

(Note:- this code is not fully optimised and the final optimised code will be uploaded within a small period after running the code for 1000 more epochs.)
