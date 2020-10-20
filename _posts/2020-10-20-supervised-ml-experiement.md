---
layout: post
title: 'Supervised ML Experiment'
date: 2020-10-20
tags:[technical, machine learning, supervised learning]
comments: true
---
> Last update on 20 Oct 2020 <br> 最后更新于2020年10月20日

# Term

**Features** are transformations of input data resulting in numerical features that facilitate a downstream algorithm to produce correct outcomes on new data. 

**Hyperparameters** are those which we supply to the model. <br> 
e.g. : number of hidden nodes and layers, input features, learning rate, activation function in neural network

**Parameters** are those which would be learned by the machine. <br>
e.g. : weights and biases

# Error Handling

**Bias** refers to the error due to overly-simplistic assumptions or faulty assumptions in the learning algorithm. A high bias means our learning algorithm is missing important trends amongst the features. <br>
Bias -> under-fitting 

**Variance** refers to the error due to an overly-complex that tries to fit the training data as closely as possible. The learning algorithm copies the training data’s trends and this results in loss of generalisation capabilities. <br>
High Variance -> over-fitting.

**Trade-off** is a balance achieved between two desirable but incompatible features; a compromise.

![Bias vs Variance](/assets/img/post-bias_variance.png)

$$
  error(x) = noise(x) + bias(x) + variance(x)
$$

# Dataset Split

Generally, the dataset is split to train and test set with common ratio 7:3 or 8:2. A good practice is to have validation set, which is split among train set.
