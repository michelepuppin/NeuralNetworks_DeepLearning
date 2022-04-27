# Neural Networks and Deep Learning
Exercises of Neural Networks and Deep Learning course in Python

## Homework 1
In this homework we will implement and test simple neural network models for solving supervised problems. Firstly,
we will consider a regression task that consists in a simple function approximation problem and we will use a deep
feed-forward neural network. Secondly, we will consider a classification task that consists in a simple image
recognition problem, where the goal is to correctly classify images of handwritten digits (MNIST). Here we will use
a convolutional neural network. In particular, advanced optimizers and regularization methods will be implemented
and learning hyperparametwrs will be tuned using appropriate search procedures.
These models are implemented in Python using the PyTorch framework.

## Homework 2
In this homework we will implement and test simple neural network models for solving unsupervised problems,
where the network is asked to learn an internal representation of the environment that can be later exploited for
other learning porpouses. Firstly, we will test and analyze a convolutional autoencoder over a dataset of images of
handwritten digits (MNIST). In particular, advanced optimizers and regularization methods will be implemented and
learning hyperparameters will be tuned using appropriate search procedures. Moreover we will implement denoising
convolutional autoencoder, where some noise is added to the input image and the network is trained to remove the
noise. Then, we fine-tune the convolutional autoencoder using a supervised classification task, we explore the latent
space structure and generate new samples from latent codes. Finally, we implement variational autoencoder which
are analogous model based on a probabilistic approach.
These models are implemented in Python using the PyTorch framework.

## Homework 3
In this homework we will implement and test neural network models for solving reinforcement learning problems,
where intelligent agents have to take actions in an environment in order to maximize the notion of cumulative reward.
In particular we consider Deep Q-learning where a Q-value function determines how good a certain action is, given
a state, for an agent following a policy. Since the computation of Q-values directly through value iterations is
computationally demanding, we can use deep neural networks to estimate the optimal Q-function.
We will train the models in different virtual environments provided by gym library. First of all, we train a Deep
Q-learning algorithm on the Cart-Pole environment, where the agent scope is to balance a pole standing on a cart by
moving the cart itself. Secondly, we train an similar algorithm on the Cart-Pole environment but using screen pixels
as input for the agent. Finally, we test the algorithm on a different environment, the Mountain-Car, where car has to
climb a mountain.
These models are implemented in Python using the PyTorch framework.
