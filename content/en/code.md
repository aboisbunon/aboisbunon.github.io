+++ 
title = "Software"
draft = false
slug = "code"
+++ 

You can find here a few [Matlab](http://www.mathworks.fr/products/matlab/) and [Python](https://www.python.org/) programs.

### Python Optimal Transport (POT)

I contributed to this awesome Python library for optimal transport mostly developped by [Rémi Flamary](http://remi.flamary.com/), [Nicolas Courty](https://people.irisa.fr/Nicolas.Courty/) and [Alexandre Gramfort](http://alexandre.gramfort.net/). I wrote a Medium article with a simple introductory example to optimal transport, you can check it [here](https://towardsdatascience.com/hands-on-guide-to-python-optimal-transport-toolbox-part-1-922a2e82e621).

[[Git Repository]](https://github.com/PythonOT/POT)


### Model Selection Toolbox (MST)

A Matlab toolbox I developped during my PhD, including many methods from the literature, both for building collections of models (Lasso, Adalasso, Elastic net, MCP, ...), and for selecting the best model from the collection (estimators of loss, AIC, AIC3, AICc, Cp, BIC, CV, SRM, slope heuristics, ...).

[[Git Repository]](https://github.com/aboisbunon/mst)


### Regularization path algorithms for LARS and MCP

The Minimax Concave Penalty (MCP) is a method developed by Zhang that keeps Lasso's selection while reducing its bias in estimation. Although it corresponds to a nonconvex and non differentiable optimization problem, the use of Clarke differentials allows to compute the optimality conditions and we were thus able to provide a regularization path algorithm similar to that of Lasso. 

[[Matlab MCP]](http://aurelie.boisbunon.free.fr/downloads/monMCP.m)
[[Matlab Lasso]](http://aurelie.boisbunon.free.fr/downloads/monLAR.m)
[[Example]](http://aurelie.boisbunon.free.fr/downloads/ex_reg_path_MCP.m)

 
### Spherically symmetric random generation

Spherically symmetric distributions are a generalization of the multivariate spherical Gaussian distribution where the assumption of independence is relaxed. The following pdf file gives an overview of the properties of the spherical family as well as the algorithms used to generate spherical random vectors. 

[[Matlab code]](http://aurelie.boisbunon.free.fr/downloads/randSS.m)
[[Example]](http://aurelie.boisbunon.free.fr/downloads/ex_random_gener.m)
[[PDF]](http://aurelie.boisbunon.free.fr/downloads/loisSS.pdf)


