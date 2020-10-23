---
layout: post
title: 'Machine Learning (ML) Overview'
date: 2020-10-20
tags: [technical, machine learning]
comments: true
---
> Last update on 23 Oct 2020 <br> 最后更新于2020年10月23日

# Approach: Conventional vs ML

Conventional: Data + Algorithm = Output <br>
ML: Data + Output = Algorithm

# ML Tribes (According to Pedro Domingos):

- Evolutionaries: learning structure [genetic programming]
- Connectionists: reverse engineer [backpropagation]
- Symbolists: manipulating symbols [inverse deduction]
- Bayesians: probabilistic inference [Bayes’ theorem]
- Analogizers: recognizing similarities [support vector machine]

# Learning Types

1. **Supervised Learning <监督学习>**: learned labelled data for future prediction
   * **classification**
   * **regression**
   * **structured prediction / structured learning**
1. **Unsupervised Learning <非监督学习>**: find relationship in unlabelled datacand does not give the right output but explores the data
   - **clustering**
      - k-means
      - DBSCAN
   - **dimension reduction**: example of application: word embedding
      - PCA
      - t-SNE
      - Autoencoder
   - **generation**
1. **Reinforcement Learning <强化学习>**: how software agents ought to take actions in an environment in order to maximize the notion of cumulative reward
   * Typical environment: Markov decision process (MDP)
1. **Semi-supervised Learning <半监督学习>**: combines a small amount of labeled data with a large amount of unlabeled data during training
   * **transductive learning**: infer the correct labels for the given unlabeled data
   * **inductive learning**: infer the correct mapping from X to Y
1. **Transfer Learning / Inductive Transfer <迁移学习>**: storing knowledge gained while solving one problem and applying it to a different but related problem
   *  Algorithm: Markov logic networks; Bayesian networks
1. **Adversarial Learning <对抗学习>**
   

