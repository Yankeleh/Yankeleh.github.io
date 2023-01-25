---
title: 'Density of powers'
date: 2023-01-24
permalink: /posts/2023/01/density-of-powers/
tags:
  - Measure Theory
  - 
---

**Problem:** Show that for almost every $x>1$ that {$x^k\mod 1$} is dense in $[0,1]$.

Let $E$ denoote the set of $x\in \mathbb{R}$ whose powers are not dense (mod 1). We may write

$$E=\bigcup_n \bigcup_{m=0}^{n-1} \{x\mid x^k \mod 1 \notin [\frac{m}{n},\frac{m+1}{n}]\},$$

and we will denote the sets being unioned as $E_{m,n}$.

Now suppose (for the sake of contradiction) that some $E_{m,n}$ had positive measure. By Lebesgue's density theorem, take $I=[a,b]$ to be an interval such that $\mu(I\cap E_{m,n})> (1-\varepsilon_0) \mu(I)$, where $\varepsilon_0$ is chosen to be much smaller than $1/n$.

If $f_k$ is given by the $k$-th root then note that

$$f_k\left(\mathbb N + \left[\frac{m}{n},\frac{m+1}{n}\right]\right) \cap I \supset f_k\left(\bigcup_{\ell=\lceil a\rceil}^{\lfloor b^k\rfloor -1} \left[\ell+\frac{m}{n},\ell+\frac{m+1}{n}\right]\right).$$

The measure of this latter set can be computed as

$$\sum_{\ell=\lceil a^k\rceil}^{\lfloor b^k\rfloor -1}\int_{\ell+m/n}^{\ell+(m+1)/n}f_k'(t) dt\geq \sum \frac{1}{kn} \left(\ell + \frac{m+1}{n}\right)^{1/k - 1}\geq \frac{1}{kn}\sum \ell^{1/k -1}.$$

By comparing this last term with $\int t^{1/k - 1}dt$, we see that it is comparable to $(b-a)/n = \mu(I)/n$. However since this is a lower bound for the measure of a set which is contained in $I$ and is disjoint from $E_{m,n}\cap I$, we have a contradiction.