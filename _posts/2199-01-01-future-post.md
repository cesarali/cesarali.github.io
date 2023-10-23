---
title: 'Future Blog Post'
date: 2199-01-01
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---

Generative Modelling
======

Definitions
======

First comes the flow:

\begin{equation}
\frac{d \phi_t(x)}{d t}=v_t\left(\phi_t(x)\right) ; \quad \phi_0(x)=x
\end{equation}

This defines a pushforward in the probability:

\begin{equation}
p_t(x)=\left[\phi_t\right]_{\#} p_0(x)=p_0\left(\phi^{-1}(x)\right)\left|\operatorname{det} \nabla_x \phi_t^{-1}(x)\right|
\end{equation}

This is related to the Wasserstein Distance:

\begin{equation}
W\left(q_0, q_1\right)_2^2=\inf _{\pi \in \Pi} \int_{\mathcal{X}^2} c(x, y)^2 \pi(d x, d y)
\end{equation}

The dynamical wasserstein distance:

\begin{equation}
W\left(q_0, q_1\right)_2^2=\inf _{p_t, u_t} \int_{\mathbb{R}^d} \int_0^1 p_t(x)\left\|u_t(x)\right\|^2 d t d x
\end{equation}
