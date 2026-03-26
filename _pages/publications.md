---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research sits at the intersection of complex analysis, hyperbolic geometry, and low-dimensional topology. The central objects are **holomorphic and antiholomorphic dynamical systems** — maps on the Riemann sphere whose iteration produces intricate fractal geometry. A recurring theme is the **Fatou-Sullivan dictionary**, an analogy between the theory of rational maps (iteration of polynomials and rational functions) and Kleinian groups (discrete groups of Möbius transformations). My work extends and makes this dictionary precise in the setting of Schwarz reflection maps and antiholomorphic correspondences, which simultaneously generalize both sides of the dictionary. The techniques draw on quasiconformal geometry, Teichmüller theory, combinatorial methods (dessins d'enfants), and renormalization theory.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
