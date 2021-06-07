---
title: 'Fundamental Groups of Cantor Set Complements'
date: 2020-12-07
permalink: /posts/2020/12/cantor-complement-fundamental-group/
tags:
  - Real Analysis
  - Topology
---

###All Cantor Sets are Homeomorphic

A _Cantor set_ is a (nonempty) compact, totally disconnected, topologcial space with no isolated points. The first example of a Cantor set was the so-called "middle thirds" Cantor set, obtained as the intersection of the decreasing sequence

$$[0,1],[0,1/3]\cup[2/3,1],[0,1/9]\cup [2/9,1/3]\cup [2/3,7/9]\cup[8/9,1].$$

Another example of a Cantor set is the infinite product $\{0,1\}^{\mathbb N}$ (that is, sequences of 0s and 1s) taken with the product topology. That is, we say two sequences are close when all of the first $N$ terms agree.

The first theorem on Cantor sets is that they are all homeomorphic

**Theorem:**Let $C$ be a Cantor set. Then $C$ is homeomorphic to $\{0,1\}^{\mathbb N}$.

_Proof Sketch:_ Take a nontrivial (cl)open set $U_0\subset C$ and call its complement $C_1$. Then for $U_i$ take a nontrivial (cl)open subset $U_{i0}$ and call $U_i\setminus U_{i0}=U_{i1}$. That is, for example, $U_1 = U_{10} \cup U_{11}$. Repeat this infinitely many times. Any inifinite sequence of 0s and 1s corresponds to a unique decreasing sequence of such (compact) sets. Any such sequence will limit to a single point; if not, we would be able to derive a contradiction to the compactness of $C$. This gives a map $h\colon {0,1}^{\mathbb N}\to C$, which can be checked to be a homemorphism.

