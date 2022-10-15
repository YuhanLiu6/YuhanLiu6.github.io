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
1.Numerical simulation of elliptic equation and Allen-Cahn equation (MATLAB).

2.Paper review on *[Deep Neural Networks as Gaussian Processes](https://arxiv.org/abs/1711.00165)*.

3.Diagnosing and Forecasting Beijing PM2.5 (Python). 

4.Checkers Programming Project (Java). 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
