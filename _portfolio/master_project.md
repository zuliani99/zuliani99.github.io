---
title: "Active Learning strategy using Graph Transduction Game"
excerpt: "Newer Active Learning strategy based on Graph Transduction Game"
collection: portfolio
---

**Active Learning (AL)** aims to leverage the performance of deep models by selecting the most valuable samples to be annotated from a pool of unlabelled data to be annotated and moved into the labeled-training set. On the other hand **Game Theory** deals with the study of strategic interactions between rational decision-makers, which are modeled as games.

Our work wants to connects these two fields by applying the **Graph Trasduction Game** which formulates the classification task as an *evolutionary non-cooperative game* between *N players* (samples) with *M strategies* (labels). Reaching a **Nash Equilibria** corresponds to find stable point of a dynamical system, one reached, all the samples are labeled consistently. To this end, the selection of samples to be labelled in the AL model, is based on:

1. Tracking the evolution of the **entropy** along the iteration of the aforementioned dynamical system
2. Creating an ad-hoc payoff function such that similar samples (already seen) are discouraged to emerge in the subsequent iterations.

We exploit the performance of our approach on five publicly available image classification benchmark: **CIFAR10/100**, **SVHN**, **Fashion-MNIST** and **Tiny-ImageNET**.