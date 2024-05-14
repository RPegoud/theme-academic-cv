---
title: Temporal-Difference Learning and the importance of exploration, An illustrated guide
date: '2023-09-23'
summary: Comparing model-free and model-based RL methods on a dynamic grid world
---

This article has been published on [**Towards Data Science**](https://towardsdatascience.com), read it [**here**](https://towardsdatascience.com/temporal-difference-learning-and-the-importance-of-exploration-an-illustrated-guide-5f9c3371413a)!

## Intro

Recently, Reinforcement Learning (RL) algorithms have received a lot of traction by solving research problems such as protein folding, reaching a superhuman level in drone racing, or even integrating human feedback in your favorite chatbots.

Indeed, RL provides useful solutions to a variety of sequential decision-making problems. Temporal-Difference Learning (TD learning) methods are a popular subset of RL algorithms. TD learning methods combine key aspects of Monte Carlo and Dynamic Programming methods to accelerate learning without requiring a perfect model of the environment dynamics.

In this article, we’ll compare different kinds of TD algorithms in a custom Grid World. The design of the experiment will outline the importance of continuous exploration as well as the individual characteristics of the tested algorithms: Q-learning, Dyna-Q, and Dyna-Q+.

The outline of this post contains:

* Description of the environment
* Temporal-Difference (TD) Learning
* Model-free TD methods (Q-learning) and model-based TD methods (Dyna-Q and Dyna-Q+)
* Parameters
* Performance comparisons
