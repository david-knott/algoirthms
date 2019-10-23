3 Layers of nodes, input layer, hidden layer and output layer

Each node ( except for input nodes ) is a neuron with an activation function.


Activation Function, defines the output of a node given an input

Layers, 3 or more layers, of non linearly activating nodes. Each node in one layer connects with a certain weight w, to every node in the following layer


Learning occurings by changing the connection weights after each epock based on the amount of error in the output compared to the expected result.
This is also known as supervised learning, via backpropagation.

degree of error in node j for the nth datapoint ( training example  ) by ej(n) = dj(n) - yj(n_), where dis the target value and y is the value producted by the
perceptron. 

The node weights can then be adjust based on the corrections that minimise the error in the entire output.

E(n) = 1/2 sum (e * e)(n)



Neuron

Outputs -> Connects to other Neuros in following layer

Inputs -> Connects to other Neurons in preceeding layer

Weights -> One for each input plus a bias input, initialized to small random values between 0 and 0.3

Activation Function -> used to calculate output based on an input

Linear like > 0.5, then output 1 otherwise 0
Non Linear sigmoidial or hyperpolic, rectifier activation function

Scaling, normalize the data

Training, stochastic gradient descent

One row of data at a time feed into metwork, which produces an output value
Output is compared to expected output and an error is calculated. Error is
then propagated back through the network, one layer at a time and weights
updated according the amount they contributed to the error. AKA Backpropagation Algorithm

Each round of processing on the dataset is called an epoch

https://machinelearningmastery.com/neural-networks-crash-course/


Sum the weighted inputs and pass through activation function
