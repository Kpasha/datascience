Deep Learning
===============
Deep Learning falls under the broad class of Articial Intelligence > Machine Learning.
It is a Machine Learning technique that uses multiple internal layers (**hidden layers**) of
non-linear processing units (**neurons**) to conduct supervised or unsupervised learning from data.

Some basic concepts of Deep Learning include:
  * Neuron, Perceptron
  * Neural Network (NN)
  * Convolutional Neural Network (CNN)
  * Recurrent Neural Netowk (RNN)
  
  
Playground
-----------
Tensorflow Playground is the best applicaton to learn about NN without math. 
View it here_. An excellent guide_ also gives a great background on the basics.

.. figure:: images/tensorflow_pg.png
    :width: 600px
    :align: center


.. _here: http://playground.tensorflow.org
.. _guide: https://cloud.google.com/blog/big-data/2016/07/understanding-neural-networks-with-tensorflow-playground


:Learning Rate: Determines the learning speed (0.00001 to 10)
:Activation: The activation function is what tells the perceptron to fire or not. eg. (ReLU, Tanh, Sigmoid, Linear)
:Regularizaton: Type of Regularization to reduce overfitting. ``L1``: can reduce coefficients to 0. Useful for few features. ``L1``: useful for inputs that are correlated. 
:Regularization Rate: 0 to 10
:Problem Type: Classificatoin or Regression



Other variables include adjusting the # neurons (max: 8), # hidden layers (max: 6), data type, noise, batch size.

Here's an example output of using **1 hidden layer** with **1, 2 & 3 neurons** in that layer. 
1 neuron can only split by one straight line.

.. figure:: images/tensorflow_pg1.png
    :width: 400px
    :align: center

For more complicated datasets, more hidden layers need to be added.

.. figure:: images/tensorflow_pg2.png
    :width: 600px
    :align: center
    
From these examples, we can see that a **hidden layer** contains the intelligence
in a distributed fashion using many ``neurons``, ``interconnection``, ``weights``,
``activation functions``, etc. **Deep NN** have multiple neutral networks.


Backpropagation 
---------------
Backpropagation (BP) uses training iterations where **error size** is used
to determine the updated value of each weight in the NN.

.. figure:: images/backp1.png
    :width: 600px
    :align: center
    
    
CNN
----
**Convolutional Neural Network** (CNN) is a Feedforward (FF) Neural Network (NN).
  * Designed based on animals' visual cortex. Where visual neurons progressively focus on overlapping tiles & sequentially shifts **convulation process** to cover the entire visual field.
  * Uses **Multi-Layer Perceptrons** (MLPs)
  * **ReLU** activation is often used
  * Image/video recognition, recommender systems, natural language processing

Subsampling
************
Median Value


RNN
----
**Recurrent Neural Network** (RNN)




