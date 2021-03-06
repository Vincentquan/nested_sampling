Nested Sampling
---------------

A python implementation of the nested sampling algorithm written by Stefano
Martiniani and Jacob Stevenson

![nested sampling example](nested_sampling.jpg)


This implementation uses the language of statistical mechanics (partition
function, phase space, configurations, energy, density of states) rather than
the language of bayesian sampling (likelihood, prior, evidence).  This is
simply for convenience, the method is the same.

Tools:

* built-in parallelisation on single computing node (max total number of cpu threads on a single machine)

* built-in parallelisation by distributed computing, ideal to run calculations on a cluster or across a network

* ability to save and restart from checkpoint binary files, ideal for very long calculations

* scripts to compute heat capacities and perform error analysis

See the examples for how to run the method

[![githalytics.com alpha](https://cruel-carlota.gopagoda.com/cb24e4a2592ef1a9437961574fe06490 "githalytics.com")](http://githalytics.com/js850/nested_sampling)
