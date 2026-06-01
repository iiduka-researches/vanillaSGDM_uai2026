# Vanilla SGD with Momentum Survives Heavy-Tailed Noise: Convergence Analysis without Gradient Clipping or Normalization @ UAI2026

We provide code for replication experiments.

# Abstract
Stochastic Gradient Descent (SGD) is a cornerstone of modern optimization. While its performance under heavy-tailed noise is often addressed through specialized modifications such as gradient clipping or normalization, we investigate a more fundamental question: how does vanilla SGD, particularly with momentum, perform in the presence of heavy-tailed noise?
In this paper, we refine existing convergence results for vanilla SGD and, more importantly, provide the first comprehensive convergence analysis of vanilla SGD with momentum for strongly-convex, convex, and non-convex objectives, without employing any gradient control mechanisms.
Our results demonstrate that the obtained convergence rates are inferior to the optimal rates achieved by clipped or normalized variants of SGD, thereby revealing inherent limitations of vanilla methods under heavy-tailed noise. The theoretical findings are supported by experiments on synthetic functions.

# Usage
It can be run directly in Google Colab.
