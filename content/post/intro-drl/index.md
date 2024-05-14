---
title: A Gentle Introduction to Deep Reinforcement Learning in JAX
date: '2023-11-21'
summary: Solving the CartPole environment with DQN in under a second
---

This article has been published on [**Towards Data Science**](https://towardsdatascience.com), read it [**here**](https://medium.com/towards-data-science/a-gentle-introduction-to-deep-reinforcement-learning-in-jax-c1e45a179b92)!

## Intro

Recent progress in Reinforcement Learning (RL), such as Waymo’s autonomous taxis or DeepMind’s superhuman chess-playing agents, complement classical RL with Deep Learning components such as Neural Networks and Gradient Optimization methods.

Building on the foundations and coding principles introduced in one of my previous stories, we’ll discover and learn to implement Deep Q-Networks (DQN) and replay buffers to solve OpenAI’s CartPole environment. All of that in under a second using JAX!

For an introduction to JAX, vectorized environments, and Q-learning, please refer to the content of [this story](https://towardsdatascience.com/vectorize-and-parallelize-rl-environments-with-jax-q-learning-at-the-speed-of-light-49d07373adf5).

Our framework of choice for deep learning will be DeepMind’s Haiku library, which I recently introduced in the context of [Transformers](https://towardsdatascience.com/implementing-a-transformer-encoder-from-scratch-with-jax-and-haiku-791d31b4f0dd):

This article will cover the following sections:

* Why do we need Deep RL?
* Deep Q-Networks, theory and practice
* Replay Buffers
* Translating the CartPole environment to JAX
* The JAX way to write efficient training loops
