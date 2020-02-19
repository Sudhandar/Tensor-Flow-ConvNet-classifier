# Tensor-Flow-ConvNet-classifier
Implementing a digits classifier using a Convolutional network with the help of tensorflow.

The Signs dataset is a collection of 6 signs representing numbers from 0 to 5.

Convolutional network architecture:

3 layer Convnet

CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED

### Cost graph:

<img src="images/cost_graph.png" style="width:800px;height:300px;">

Train Accuracy: 94%
Test Accuracy: 78%