---
title: 'Cantor Sets I: Some Topology'
date: 2020-06-28
permalink: /posts/2020/06/cantor-sets-i/
tags:
  - Math
  - Toplogy
  - Group Theory
---

I want to do some posts on my favorite topological space, the Cantor set. Cantor sets serve as important examples in virtually all fields of anlaysis and dynamical systems, as well as in geometric group theory and foliation theory. In this post I will describe some basic topological properties of Cantor sets, and in a following post I will describe some group actions on cantor sets.

_Definition_: A Cantor set is said to be a nonempty topological space _X_, which satisifies the following three conditions:

1. _X_ is compact.
2. _X_ is totally disconnected, i.e. the connected components of _X_ are individual points. Equivalently, we may say that every open set is also closed (and hence compact by condition 1).
3. _X_ has no isolated points. Equivalently, any neighborhood of a point $U\ni x$ will have an infinite intersection with $X$. In fact, it follows from these conditions that any nonempty open subset of a Cantor set will itself be a Cantor set.

The main theorem we will present is that all Cantor sets are homeomorphic. Before proving this however, let us see some examples.

### Cantor Sets on an Interval

The first example of such a set (due independently to Henry John Stephen Smith (1874), Paul du Bois-Reymond(1880), Vito Volterra(1881), and Georg Cantor (1883)) was constructed as follows:

Begin with the unit interval \(C_0=[0,1]\). Remove the (open) middle third of this set to obtain \(C_1 =[0,1/3]\cup[2/3,1]\). We repeat this process inductively: \(C_n\) will be a union of \(2^n\) closed intervals, and upon removing the middle thirds obtain \(C_{n+1}\). Define \(C=\bigcap C_i\), and we claim that \(C\) is a cantor set. Indeed, we check:

1. \(C\) is the decreasing intersection of compact sets it will be compact/
2. Given any two points $x_1,x_2$ in $C$ we may take an $n$ so large that $x_1$ and $x_2$ lie in different intervals of $C_n$. As they are in different components of $C_n$, they will be in different components of $C$.
3. Given any neighborhood $U$ of some point $x_0\in C$, there is some $n$ so large that the interval of $C_n$ which contains $x_0$ will lie inside of $U$. The intersection of this interval with $C$ will be infinite.

### Dynamical Cantor Sets

A nice example as to how Cantor sets appear in dynamical systems is the following: Let $f(x)=x^2-c$ where $c<-2$. The set of points $x$ for which the sequence $\{x,f(x),f(f(x)),f(f(f(x))),...\}$ will stay bounded is a Cantor set. I won't prove this fact, but it can help us visualize what a cantor set looks like. Below is the graph of the 13th iterate of such an $f$. The projection onto the x axis of what we see here is approximately a Cantor set.

(attached image)

### A Symbolic Representation

Another example of a Cantor set 

Any Cantor set can be seen to be homeomorphic to $\Sigma_2^+$ via the following process of _coding_. Let $C$ be a cantor set. If $U_0$ is a nonempty, open, proper subset of $C$, then by property 2, its complement $U_1 = C\setminus U_0$ will also be open. We can then further divide 