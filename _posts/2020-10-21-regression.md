---
layout: post
title: 'Regression'
date: 2020-10-21
tags: [technical, machine learning, supervised learning]
comments: true
---
> Last update on 21 Oct 2020 <br> 最后更新于2020年10月21日

**Regression <回归>**: find a function, through *x* feature, output a scalar value. "由果索因"

**linear regression <线性回归>**: think that vector and finalize function is in linear relationship

**nonlinear regression <非线性回归>**

**logistic regression <逻辑回归>**: estimating the parameters of a logistic model (a form of binary regression)

## Application 

Stock market forecast <股市预测> <br>
input：past stock transaction, news about the company, etc. <br>
output：stock price tomorrow

Self-driving Car <自动驾驶> <br>
input：data transmitted from sensors on the car like road condition, car distance, etc. <br>
output：angle of steering wheel

Recommendation <商品推荐> <br>
input：characteristic of item A, characteristic of item B <br>
output: probability of buying item 

## Modeling procedure with example
 
1. Hypothesis: choose a model (linear model <线性模型>) <br> 
   - **Univariate linear model <一元线性模型>**: individual features <br>
   - **Multivariate linear model <多元线性模型>**: multiple features
   
1. Evaluate: decide which is good model (loss function <损失函数>) <br>
   - the lower the better
   
1. Optimize: select the best model (gradient descent <梯度下降>)



# Reference
1. https://datawhalechina.github.io/leeml-notes/#/chapter3/chapter3
