# Scalar-BackPropagation
While designing the neural network, we initialize the weights with some random values. It is not necessary that which value is assigned to network is best fit for our model. So, the error will be high.\
We need to train our model to assign weights value which give minimum error.\
The training is done with the help of backpropagation.\
Backpropagation is a short form for "backward propagation of errors." It is a standard method of training artificial neural networks. This method helps to calculate the gradient of a loss function with respects to all the weights in the network.\
The Backpropagation algorithm looks for the minimum value of the error function in weight space using a technique called the delta rule or gradient descent. And Gradient descent is an optimization algorithm used to find the values of parameters (weights) of a function (Neural network) that minimizes a cost function (loss).\
In real-world problem we are not performing gradient descent by ourself, we have different libraries and frameworks to this heavy lifting job.


## Binary classification ##
* 2 inputs
* 1 hiden layer with 2 neurons
* output layer with 1 neuron

## Multiclass classification (4-class) ##
* 2 inputs
* 1 hinnden layer with 2 neurons
* output layer with 4 neurons

## Notations ##
* a = x * w
* h = activation(a)

