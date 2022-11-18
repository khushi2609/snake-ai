# Welcome to Snake AI

## Introduction
Reinforcement Learning is teaching a software agent how
to behave in an environment by telling it how good it’s doing.
Deep Q Learning extends reinforcement learning by using a
deep neural network to predict the actions of any agent. In
this project we have used a snake game which uses Pygame
and can be played by any user. Next, we build a model using
PyTorch. The model used here is a simple feed forward
neural net with few linear layers. Finally, we build an agent
that plays the game and trains itself using the created model
to predict the best possible move. The rewards, states and
actions for the game have been defined.

The state has 11 values. Firstly, it gives information for
whether the danger is ahead, right or left. It also states the
direction of the snake’s head and the food. All these values
are represented as boolean.
The model is a feed forward neural net with three layers
- input layer, hidden layer and output layer. The input layer
gets the 11 different states
