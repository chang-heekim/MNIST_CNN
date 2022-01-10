# MNIST_CNN

 - ### MNIST dataset
  - MNist dataset learning/validation was conducted using Google Colab.
 
 - Image
 
 
 - Hyper Parameters
   -learning_rate = 0.0001
   -epochs = 15
    
 - ### Convolution Network
 | Layer                 | Specification                                                     | 
 | :---------------------| :-----------------------------------------------------------------|
 | Input                 | Channel = 1, Image size = 28 x 28                                 |
 | Convlayer_1           | Channel = 32, kernel_size = 3 x 3, stride = 1, padding = 0(=same) |
 | Activation            | ReLU                                                              |
 | Convlayer_2           | Channel = 64, kernel_size = 3 x 3, stride = 1, padding = 0(=same) |
 | Activation            | ReLU                                                              |
 | Fully_connected_1     | number of neuron = 128                                            |
 | Activation            | ReLU                                                              |
 | Fully_connected_2     | number of nutron = 10                                             |
 | Softmax               | 10 classes                                                        |


- ### Accuracy : 92.97%


<b>[MNIST with Pytorch](/Pytorch_CNN_MNIST.ipynb)</b>
<b>[MNIST with Tensorflow](/Tensorflow_CNN_MNIST.ipynb)</b>
