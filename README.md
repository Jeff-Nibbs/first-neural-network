# My First Nueral Network

This is one of my first steps at building my own AI models.

This is a breakdown of how the code works and why...as i understand it.

## Neurons
A neuron is a basic unit of a neural network. A neuron takes inputs, does some math with them, and produces one output.

* For a 2 input neuron each input is multiplied by a weight.
* then all the weighted inputs are added together and added to the bias
* finally the sum is passed through an activation function
  * activation function is used to turn an unbounded input into an output that has a nice, predictable form
  * the activation function that I used was the  **Sigmoid** function **σ(x) = 1 / (1 + exp(-x))**
  * The sigmoid function only outputs numbers in the range (0,1)
* this is the final equation y = function( (x1 * w1) + (x2 * w2) + b)
  *  the function is σ(x) = 1 / (1 + exp(-x))

  