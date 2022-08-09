---
title: Streaming Facility Location in High Dimension via New Geometric Hashing
publication_types:
  - "1"
authors:
  - Artur Czumaj
  - Shaofeng H.-C. Jiang
  - Robert Krauthgamer
  - Pavel Veselý
  - admin
doi: https://arxiv.org/abs/2204.02095
publication: FOCS 2022
publication_short: FOCS 2022
abstract: >-
  In Euclidean Uniform Facility Location, the input is a set of clients in
  $\mathbb{R}^d$ and the goal is to place facilities to serve them, so as to
  minimize the total cost of opening facilities plus connecting the clients. We
  study the classical setting of dynamic geometric streams, where the clients
  are presented as a sequence of insertions and deletions of points in the grid
  $\{1, \ldots, \Delta \}^d$, and we focus on the \emph{high-dimensional
  regime}, where the algorithm's space complexity must be polynomial (and
  certainly not exponential) in $d \cdot \log \Delta$.

  We present a new algorithmic framework, based on importance sampling from the stream, for $O(1)$-approximation of the optimal cost using only ${\rm poly}(d\cdot \log \Delta)$ space. This framework is easy to implement in two passes, one for sampling points and the other for estimating their contribution. Over random-order streams, we can extend this to a one-pass algorithm by using the two halves of the stream separately. Our main result, for arbitrary-order streams, computes $O(d^{1.5})$-approximation in one pass by using the new framework but combining the two passes differently. This improves upon previous algorithms that either need space exponential in d or only guarantee $O(d \cdot \log^2\Delta)$-approximation, and therefore our algorithms for high-dimensional streams are the first to avoid the $O(\log \Delta)$-factor in approximation that is inherent to the widely-used quadtree decomposition. Our improvement is achieved by employing a geometric hashing scheme that maps points in $\mathbb{R}^d$ into buckets of bounded diameter, with the key property that every point set of small-enough diameter is hashed into at most poly(d) distinct buckets.


  We complement our results by showing $1.085$-approximation requires space exponential in ${\rm poly}(d \cdot \log \Delta)$, even for insertion-only streams.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-08-09T08:40:28.360Z
---
