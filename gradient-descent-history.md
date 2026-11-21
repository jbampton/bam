---
description: "How gradient descent grew from Cauchy's 1847 steepest descent to the Perceptron and modern machine learning."
keywords: ["gradient descent", "history", "Cauchy", "perceptron", "machine learning", "optimization"]
---

# The History and Evolution of Gradient Descent: From Math to Machines
Gradient descent is the mathematical engine behind modern Artificial Intelligence (AI) and machine learning. While it feels like a contemporary computing concept, its roots stretch back nearly two centuries, transitioning from hand-written astronomy equations to the first digital neural networks.
------------------------------

## 1. The Mathematical Discovery (1847)
The core concept of gradient descent was discovered and first suggested by the French mathematician Augustin-Louis Cauchy in 1847.

* The Problem: Cauchy was trying to solve complex, tedious astronomical calculations (specifically, computing the orbits of planets or light waves) without modern calculating tools.
* The Solution: He proposed an iterative method known then as "steepest descent." Instead of trying to solve a massive equation all at once, he realized you could take small, calculated steps downhill along the steepest slope (the gradient) until you found the lowest point (the minimum).

## Key Historical Milestones (Pen and Paper)

* 1847: Augustin-Louis Cauchy introduces the fundamental concept of iterative minimization using gradients.
* 1907: French mathematician Jacques Hadamard independently proposes a similar descent approach for solving differential equations.
* 1944: American logician Haskell Curry (after whom the Haskell programming language is named) conducts the first rigorous study of the formal convergence properties of the method for non-linear optimization.

------------------------------
## 2. The Dawn of Computing (1960s)
For over a century, gradient descent remained a theoretical mathematical tool. The transition from a pen-and-paper concept to executing computer code occurred during the late 1950s and early 1960s, driven by the birth of early artificial intelligence.
Because early programming was heavily decentralized, historians point to three definitive "firsts" depending on the specific field:
## I. The First "Machine Learning" Application (1960)
The Mark I Perceptron, built by Frank Rosenblatt in 1960, is widely considered the earliest physical computing system to run a gradient-like iterative correction program.

* How it worked: While the core algorithm was a specialized perceptron update rule rather than standard modern backpropagation, it mathematically mirrored the concept of taking iterative steps based on directional error to find a minimum.

## II. The First Pure Nonlinear Estimation Software (1966)
The earliest documented, fully digital computer program designed to explicitly use gradient descent methods for multi-variable optimization was created by Harry Eisenpress, Jean Bomberault, and J. Greenstadt in 1966.

* How it worked: Written for econometric modeling on early IBM mainframes, this program used a blend of Newton’s method and gradient descent to perform nonlinear parameter estimation across massive systems of equations.

## III. The First True Deep Learning Program (1967)
In 1967, Japanese researcher Shun-ichi Amari wrote the first computer code that successfully trained a multi-layer neural network using Stochastic Gradient Descent (SGD).

* How it worked: Amari's program proved that a computer could automatically learn internal structural representations to classify complex, non-linearly separable patterns simply by adjusting weights downward along a gradient.

------------------------------
## Chronological Summary

* 1847: Cauchy invents "Steepest Descent" for astronomy.
* 1944: Haskell Curry formalizes the convergence mathematics.
* 1960: Rosenblatt's Mark I Perceptron uses iterative error correction.
* 1966: Eisenpress, Bomberault, and Greenstadt write the first explicit digital gradient software.
* 1967: Shun-ichi Amari codes the first Stochastic Gradient Descent program for neural networks.
