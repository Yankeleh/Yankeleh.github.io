---
title: 'The Fatou-Sullivan Dictionary'
date: 2020-07-17
permalink: /posts/2020/07/fatou-sullivan-dictionary/
tags:
  - Complex Dynamics
  - Hyperbolic Geometry
---
## The Dictionary

The Fatou-Sullivan dictionary (often called Sullivan's dictionary) provides a go-between for translating objects, theorems, and conjectures between the languages of Kleinian groups and iteration of holomorphic maps. The similarity between these two worlds was first noticed by Pierre Fatou in the early days of complex dynamics, and was later rediscoverd by Dennis Sullivan who used the analogy to prove the classical "no wandering domains" theorem of complex dynamics.

Below is a table outlining every significant entry (and failure of translation) in the dictionary that I know.

Last updated July 17, 2020:

Kleinain Groups | Iterated Holomorphic Maps | Notes
--- | --- | ---
The Kleinian Group $\Gamma$ | Iterates of a holomorphic map $\{f^n\}$ |
A finitely generated Kleinian group | A rational map |
The domain of discontinuity, or ordinary set $\Omega$ | The Fatou set $\mathcal {F}(f)$ | Both of these can be defined as the set of points in which $\Gamma$ or $\{f^n\}$ forms a normal family on a neighborhood.
The limit set $\Lambda(\Gamma)=\hat{\mathbb{C}}\setminus \Omega(\Gamma)$ | The Julia set $J(f)=\hat{\mathbb{C}}\setminus \mathcal{F}(f)$ |
Fixed points of $\Gamma$, i.e. satisfying $z = \gamma(z)$ for some $\gamma$| Preperiodic points, i.e. satisfying $f^n(z)=f^m(z)$ for some $m,n$ |
$\Lambda(\Gamma)$ is nonempty with no interior | $J(f)$ is nonempty with no interior |
$\Omega(\Gamma)$ has 0,1,2 or infinitely many connected components | $J(f)$ has 0,1,2 or infinitely many connected components |
Ahlfors's Finiteness Theorem | Sullivan's no wandering domains theorem |
Bers's Finiteness Theorem | Shishikura's bound on periodic orbits |
Thurston's geometrization theorem for Haken manifolds | Thurston's theorem on the realization of postcritically finite topological maps as rational maps |
Mostow's rigidity theorem | Thurston's uniqueness theorem for postcritically finite rational maps |
The Riemann surfaces $\Omega(\Gamma)/\Gamma$ | Riemann surface laminations for rational maps |
The 3-manifold $\mathbb{H}^3/\Gamma$ | Lyubich-Minsky laminations |
Patterson-Sullivan Measures on $\Lambda(\Gamma)$ | Sullivan's conformal measures on $J(f)$ |
??? | The measure of maximal entropy for a rational map |
Geometrically finite groups without cusps are dense | Are hyperbolic maps dense? | The conjecture here is perhaps the largest open problem in complex dynamics
| Structurally stable maps are dense |
Structurally stable groups are geometrically finite without cusps | Does structural stabiliy imply hyperbolicity? |
There are no invariant line fields on $\Lambda(\Gamma)$ | Are there invariant line fields on $J(f)$ when $f$ is not a Lattes example? |
The ending lamination theorem | Is the Mandelbrot set locally connected? | 
The limit set $\Lambda(\Gamma)$ either has zero measure or is the entire sphere | *There is a quadratic polynomial with postive measure Julia set* | This of course is a break in the dictionary
??? | Arithmetic heights for rational maps |
Two f.g. Kleinian groups which share a limit set are normal subgroups of a common group | Two rational maps which share a Julia set have commuting iterates | These statements are not quite precise and need to make exceptions