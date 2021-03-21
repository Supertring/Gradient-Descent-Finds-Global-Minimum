# Gradient-Descent-Finds-Global-Mimimum

Gradient descent is an algorithm to perform optimization
of neural network. In a neural network the objective
function will have several minimum values and one of them is the
global minimum. To ensure trainability and generalizability of a
neural network finding global minimum is very important. Some
of widely used methods to overcome local minima and achieve
global minima are over-parameterization of neural network,
Gaussian initialization of weight, defining upper, lower bound
of input size and hidden number of nodes per layer etc.

Algorithms like CNN, RNN, LSTM, DQN are used to solve
problems in various fields, autonomous driving is one of them.
Autonomous driving make use of these and many other algorithms
in all the stages : Perception, Planning & Control, to
make the vehicle intelligent and gradient descent is extensively
used to optimize these algorithms. From literature research and
experiment performed on MNIST datasets with CNN, practical
degree of over-parameterization was found to be the best method
to find global minimum.

This implementation is to show the change in trainability
and generalizability of the neural network due to the change
in parameters of the network. Here gradient descent acts as
a bridge and a tool to make change in trainability and generalizability
using given parameters. Focus is on Convolutional
Neural Network as it is widely used in autonomous vehicles
for perception problems and MNIST datasets is used for the
experiment. The experiment is done in three different settings
as follows.
 Under-parameterization: Number of trainable parameters
are tremendously less than the number of training samples.
 Over-parameterization: Number of trainable parameters
are tremendously more than the number of training samples.
 Practical degree of over-parameterization: Total number
of trainable parameters are in the order of n, where n is
the number of training samples.
