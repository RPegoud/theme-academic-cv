---
title: Vectorize and Parallelize RL Environments with JAX, Q-learning at the Speed of Light
date: '2023-10-15'
summary: Solving the CartPole environment with DQN in under a second
---

This article has been published on [**Towards Data Science**](https://towardsdatascience.com), read it [**here**](https://towardsdatascience.com/vectorize-and-parallelize-rl-environments-with-jax-q-learning-at-the-speed-of-light-49d07373adf5)!

## Intro

In the [**previous story**](https://towardsdatascience.com/temporal-difference-learning-and-the-importance-of-exploration-an-illustrated-guide-5f9c3371413a), we introduced Temporal-Difference Learning, particularly Q-learning, in the context of a GridWorld.

While this implementation served the purpose of demonstrating the differences in performances and exploration mechanisms of these algorithms, it was painfully slow.

Indeed, the environment and agents were mainly coded in Numpy, which is by no means a standard in RL, even though it makes the code easy to understand and debug.

In this article, we’ll see how to scale up RL experiments by vectorizing environments and seamlessly parallelizing the training of dozens of agents using JAX. In particular, this article covers:

* JAX basics and useful features for RL
* Vectorized environment and why they are so fast
* Implementation of an environment, policy, and Q-learning agent in JAX
* Single-agent training
* How to parallelize agent training, and how easy it is!
