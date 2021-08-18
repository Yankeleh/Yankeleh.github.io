---
title: 'The Fatou-Sullivan Dictionary'
date: 2020-07-17
permalink: /posts/2020/07/fatou-sullivan-dictionary/
tags:
  - Complex Dynamics
  - Hyperbolic Geometry
---

(A lot of this table/post was written quickly and needs reorganization/explanation/citations.)

## The Dictionary

The Fatou-Sullivan dictionary (often called Sullivan's dictionary) provides a go-between for translating objects, theorems, and conjectures between the languages of Kleinian groups and iteration of holomorphic maps. The similarity between these two worlds was first noticed by Pierre Fatou in the early days of complex dynamics , and was later rediscoverd by Dennis Sullivan who used the analogy to prove the classical "no wandering domains" theorem of complex dynamics.

Below is a table outlining every significant entry (and failure of translation) in the dictionary that I know. 

Last updated July 17, 2020:

| Kleinain Groups | Iterated Holomorphic Maps | Notes
--- | --- | --- | ---
| The Kleinian Group $\Gamma$ | Iterates of a holomorphic map $\{f^n\}$ |
| A finitely generated Kleinian group | A rational map |
| The domain of discontinuity, or ordinary set $\Omega$ | The Fatou set $\mathcal {F}(f)$ | Both of these can be defined as the set of points in which $\Gamma$ or $\{f^n\}$ forms a normal family on a neighborhood.
| The limit set $\Lambda(\Gamma)=\hat{\mathbb{C}}\setminus \Omega(\Gamma)$ | The Julia set $J(f)=\hat{\mathbb{C}}\setminus \mathcal{F}(f)$ |
| Fixed points of $\Gamma$, i.e. satisfying $z = \gamma(z)$ for some $\gamma$| Preperiodic points, i.e. satisfying $f^n(z)=f^m(z)$ for some $m,n$ |
| $\Lambda(\Gamma)$ is nonempty with no interior | $J(f)$ is nonempty with no interior |
| $\Omega(\Gamma)$ has 0,1,2 or infinitely many connected components | $J(f)$ has 0,1,2 or infinitely many connected components |
| A finite index subgroup $\Gamma' < \Gamma$ | An iterate of the original map $f^k$ |
| An arbitrary subgroup | ??? | It doesn't seem as though there's a good analogy for this
| Ahlfors's Finiteness Theorem | Sullivan's no wandering domains theorem |
| Bers's Finiteness Theorem | Shishikura's bound on periodic orbits |
| Thurston's geometrization theorem for Haken manifolds | Thurston's theorem on the realization of postcritically finite topological maps as rational maps |
| Simultaneous uniformization of two surface groups to obtain a quasifuchsian group | Quasiconformal mating of rational maps, e.g. mating a Blaschke product with the $z^2$ map to obtain $f(z)=z^2+\varepsilon$|
| Mostow's rigidity theorem | Thurston's uniqueness theorem for postcritically finite rational maps |
| The Riemann surfaces $\Omega(\Gamma)/\Gamma$ | Riemann surface laminations for rational maps |
| The 3-manifold $\mathbb{H}^3/\Gamma$ | Lyubich-Minsky laminations |
|Patterson-Sullivan Measures on $\Lambda(\Gamma)$ | Sullivan's conformal measures on $J(f)$ |
| ??? | The measure of maximal entropy for a rational map | Harmnoic measures might provide a useful analogy on the group side
| Geometrically finite groups without cusps are dense | Are hyperbolic maps dense? | The conjecture here is perhaps the largest open problem in complex dynamics
| | Structurally stable maps are dense |
| Structurally stable groups are geometrically finite without cusps | Does structural stabiliy imply hyperbolicity? |
| There are no invariant line fields on $\Lambda(\Gamma)$ | Are there invariant line fields on $J(f)$ when $f$ is not a Lattes example? |
| The ending lamination theorem | Is the Mandelbrot set locally connected? | 
|The limit set $\Lambda(\Gamma)$ either has zero measure or is the entire sphere | *There is a quadratic polynomial with postive measure Julia set* | This of course is a break in the dictionary
| ??? | Arithmetic heights for rational maps |
| Two f.g. Kleinian groups which share a limit set are normal subgroups of a common group | Two rational maps which share a Julia set have commuting iterates | These statements are not quite precise and need to make exceptions
| Any closed hyperbolic surfaces have finite covers which are close in the Teichmuller metric | Let $f_1,f_2$ be Blaschke products (with Julia set the circle) and $\varepsilon>0$ be given. Are there $n, m$ such that $f_1^n$ and $f_2^m$ are quasiconformally conjugate with dilatation bounded by $1+\varepsilon$? | The theorem for groups is the so-called "Ehrenpreis conjecture" which was proven by Jeremy Kahn and Vlad Markovic. The question for rational maps is false as stated - we need a condition about periodic orbits of critical points to ensure that the maps will even have toplogically conjugate iterates.
| Every co-compact Kleinian group has a subgroup which is isomorphic to the fundamental group of a surface | ??? | See number 9 for my main source of confusion as to how to translate this question