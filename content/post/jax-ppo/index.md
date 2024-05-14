---
title: Breaking down State-of-the-Art PPO Implementations in JAX
date: '2024-05-01'
summary: All the tricks and details you wish you knew about Proximal Policy Optimization
---

This article has been published on [**Towards Data Science**](https://towardsdatascience.com), read it [**here**](https://medium.com/towards-data-science/breaking-down-state-of-the-art-ppo-implementations-in-jax-6f102c06c149)!

## Intro

Since its publication in a 2017 paper by OpenAI, Proximal Policy Optimization (PPO) is widely regarded as one of the state-of-the-art algorithms in Reinforcement Learning. Indeed, PPO has demonstrated remarkable performances across various tasks, from attaining superhuman performances in Dota 2 teams to solving a Rubik’s cube with a single robotic hand while maintaining three main advantages: simplicity, stability, and sample efficiency.

However, implementing RL algorithms from scratch is notoriously difficult and error-prone, given the numerous error sources and implementation details to be aware of.

In this article, we’ll focus on breaking down the clever tricks and programming concepts used in a popular implementation of PPO in JAX. Specifically, we’ll focus on the implementation featured in the PureJaxRL library, developed by Chris Lu.
