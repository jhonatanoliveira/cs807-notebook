---
published: true
title: The Problem
layout: post
---

The purpose of the research task C is to find a academic problem in which we can apply parallel techniques. More specific, we want to be able to use a GPU device to achieve faster run of that problem.

For the paper research task, we discussed a very interesting idea deep model for learning and inference with probabilities, called [Sum-Product networks](http://spn.cs.washington.edu/).
These models are represented as a directed acyclic graph. Inference is then performed by propagating information in this graph from bottom up and the other way around.
The problem analyzed then is how to parallelize these computation when propagating in this tree.

Follows the abstract of the written [paper](https://github.com/jhonatanoliveira/cs807-research-tasks/blob/master/the_problem/the_problem.pdf):Sum-product networks (SPNs) are a layer-wise mathematical models for learning and inference with probabilistic graphical model. The main advantage of SPNs is that a learned model, under certain conditions, is guaranteed to have tractable inference in polynomial time, besides of inference being exact. Given a SPN, inference is done by propagating up on the network. In this paper, it is shown how the propagation can be done in parallel.