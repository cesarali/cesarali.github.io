---
title: "Amazon StatML Workshop 2024"
collection: talks
type: "Talk"
permalink: https://statml24.splashthat.com/
venue: "Amazon's Berlin office in Germany"
date: 2024-04-17
location: "Berlin"
---

In this work, we introduce a novel con nuous- me framework for the genera ve modeling of discrete data through 
a noising process based on Condi onal Markov Bridges. We model the evolu on of the system as a Con nuous Time 
Markov Chain (CTMC), in the form of a Markov Jump Process. In the genera ve modeling problem, one has access 
to samples of the process $(x_0, x_1)$ at ini al ($t=0$) and final mes ($t=1$), which are assumed to be drawn from 
a \tex t{joint probability} $q_{0,1}(x_0, x_1)$ with given marginals $q_0(x_0)$ and $q_1(x_1)$. We construct a 
CTMC, which we call the target process, that has the correct joint marginals $q_{0,1}(x_0, x_1)$. This is achieved by 
marginalizing the rate of the condi onal Markov bridge over the joint \tex t{posterior probability} of the ini al and 
end states. We efficiently accomplish this by learning a parametric esmate of the posterior probability, obtained by 
sampling data and a bridge, with the assistance of a dynamic classifier. The approach draws parallels to Schrödinger 
bridges but is achieved in one training round without the need for Sinkhorn itera ons. 