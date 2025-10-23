# torics_from_feynman_integral
A simple Jupyter notebook written using SymPy to find the toric equation satisfied by a GKZ integral representing a Feynman integral. The code takes any Feynman integral written in (post Wick rotation) momentum space parameterised in terms of a loop momentum k, applied Schwinger's trick to find the First and Second Symanzik polynomials. From here it gets its associated A matrix and kernel vectors to find the toric equations satisfied by the integral.

Currently works only if the Feynman integral is parametrised in terms of a single loop momentum k. 
