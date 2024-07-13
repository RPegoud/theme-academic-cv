---
title: Rainbow, The Colorful Evolution of Deep Q-Networks
date: '2024-07-12'
summary: Everything you need to assemble the DQN Megazord in JAX.
---

This article has been published on [**Towards Data Science**](https://towardsdatascience.com), read it [**here**](https://medium.com/towards-data-science/rainbow-the-colorful-evolution-of-deep-q-networks-37e662ab99b2)!

## Intro

In 2013, the introduction of Deep Q-Networks (DQN) by *Mnih et al.* marked the first breakthrough in Deep Reinforcement Learning, surpassing expert human players in three Atari games. Over the years, several variants of DQN were published, each improving on specific weaknesses of the original algorithm.

In 2017, *Hessel et al.* made the best out of the DQN palette by combining 6 of its powerful variants, crafting what could be called the DQN Megazord: Rainbow.

In this article, we’ll break down the individual components that make up Rainbow, while reviewing their JAX implementations in the Stoix library.
