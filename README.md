# Transformer using Numpy
Using Portuguese OList product reviews, build a Numpy based transformer for emotion classification. This implementation is very crude and not optimized for speed.

# Model specifications

* Number of attention heads : 8
* embedding size : 256
* output units : 2
* Number of hidden units in fully connected network portion: 512

# Training
* Number of epochs : 100
* Time taken : 1hr 30 mins
* Train accuracy : 97%
* Test accuracy : 82%

# Optimizer Used : Adam Optimizer

Optimizer Parameters
* beta1 = 0.9
* beta2 = 0.999
* epsilon = 1e-8
* learning_rate = 0.001

# Training Loss vs Epochs

![Training Loss vs Epochs](https://raw.githubusercontent.com/adhok/Transformer_using_Numpy/main/output.png)
