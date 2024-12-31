# Algorithms for ridge estimation with convergence guarantees

This repository contains the R codes for the following article: 

Algorithms for ridge estimation with convergence guarantees.  
Qiao, W. and Polonik. W. (2021). https://arxiv.org/abs/2104.12314.

## Abstract

The extraction of filamentary structure from a point cloud is discussed. The filaments are modeled as ridge lines or higher dimensional ridges of an underlying density. We propose two novel algorithms, and provide theoretical guarantees for their convergences, by which we mean that the algorithms can asymptotically recover the full ridge set. We consider the new algorithms as alternatives to the Subspace Constrained Mean Shift (SCMS) algorithm for which no such theoretical guarantees are known.

## Description

- "ancillary.r": collection of R functions for ridge estimation algorithms

- "spiral.r": R code for an example of spiral data

- "cross.r": R code for an example of X-cross data

- "circle.r": R code for an example of circle data

- "volcano.r": R code for a real data example (volcanoes in Japan)

- "CounterExample.r": R code for an example for which SCMS fails to find the entire ridge but our new algorithms work.

