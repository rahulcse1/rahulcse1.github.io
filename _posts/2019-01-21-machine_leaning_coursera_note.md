---
layout: post
title: Machine Learning Coursera Note
tags: [machine_learning,coursera]
---

## My Learning with coursera [Machine Learning Coursera Note]

ML : gives computer the ability to learn with being explicilty programmed 

A computer program is said to learn from experience E with respect to some class of task T and performance p, if it's performance as task T as measured by P improves with experience E

Example: playing checkers.

E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.

Machine Learning Problems
  - Supervised Learning : we are given a dataset and we already know what our output should looklike , having the idea that there is a relationship between input and the output.
    - Regression :  trying to predict results within a countinous output
    - Classification : trying to predict results in discrete output
  - Unsupervised Learning : No information about data or very minimal information ex google news: grouping newz in diff cluster 
    - clustering
  - reinforcement learning

Linear regression h(x) = θ0 + θ1x 
#Cost fundtion:
  - cost fundtion will let us figure out the best possible staright line to our data.
  - choosing best possible thera values 
  - we have to choose the value of θ0 and θ1 in such a way for given dataset that value of h(x) value we predict on input x is close to the value of y.

#Gradient Descent: Algorithm to used to minimizing cost function
  
