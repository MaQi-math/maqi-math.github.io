---
title: 'Introduction to Navier-Stokes Equations'
date: 2024-12-25
permalink: /posts/2024/12/intro-NS/
tags: - Navier-Stokes eqn
---

Navier-Stokes equations describe the viscous imcompressible flow. It is a PDE system taking the following form:

$$\begin{align} \partial_t u - \nu \Delta u + u\cdot \nabla u + \nabla p = f \\
    \mbox{div } u = 0\end{align}$$

where $u:\ \mathbb{R}^n \times \to \mathbb{R}^n$ is a vector field, in physical model it denotes the velocity field;
$p:\mathbb{R}^n\to \mathbb{R}$ is a single-valued function, which denotes the pressure; and $f$ denotes the force in physical model

Given $f$, our goal is to find a pair of $(u,p)$ to satisfy the equations.
