---
title: "Estimating Large-Scale Tree Logit Models via a Difference of Strictly Convex Functions"
collection: publications
permalink: /publications/4-Treelogit
excerpt: 'This is a joint work with Srikanth Jagabathula and Paat Rusmevichientong.'
date: 2021-06-28
venue: 'Major Revision at Operations Research'
paperurl: 
citation: 
---
Abstract
---
We describe an efficient estimation method for large-scale tree logit models, using a novel change-of-variables
transformation that allows us to express the negative log-likelihood as a difference of strictly convex functions.
Exploiting this representation, we design a fast iterative method that computes a sequence of parameter
estimates. At each iteration, parameters at leaf nodes are updated using a simple formula involving the
Lambert-W function, while the parameters at non-leaf nodes are updated simultaneously by minimizing a
strictly convex one-dimensional function over the unit interval. No step size or second-order derivative is
required. The sequence of parameter estimates yields increasing likelihood values, and we show that every
limit point is a stationary point. Numerical results show that our algorithm outperforms state-of-the-art
optimization methods, especially for large-scale tree logit models with thousands of nodes.

