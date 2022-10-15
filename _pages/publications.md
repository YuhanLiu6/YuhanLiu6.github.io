---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Research Interests
Numerical PDE, Machine Learning in Scientific Computing, Data-driven Modeling. 

## Research Experience
1.Acceleration of Variable Frequency Fourier Transform (present)

## Course Projects
1.Numerical simulation of elliptic equation and Allen-Cahn equation

2.Paper review on *[Deep Neural Networks as Gaussian Processes](https://arxiv.org/abs/1711.00165)*

3.Programming Project of Diagnosing and Forecasting Beijing PM2.5 

4.Prediction of Decomposition Rates and Interspecific Interactions of Fungi 

5.Checkers Programming Project 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
