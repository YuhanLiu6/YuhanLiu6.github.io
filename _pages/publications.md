---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Research Interests
Scientific Computing, Numerical Analysis, Applied Mathematics, Scientific Machine Learning

## Research Projects
1.Acceleration of Variable Frequency Fourier Transform (2022 Summer)
- Working with [Prof. Zhen Zhang](https://math.sustech.edu.cn/e/zhangzhen) at SUSTech.

<!-- ## Course Projects
1.Numerical simulation of elliptic equation and Allen-Cahn equation (MATLAB).

2.Literature review on *[Deep Neural Networks as Gaussian Processes](https://arxiv.org/abs/1711.00165)*, [review](https://github.com/Hv1000/Hv1000.github.io/blob/master/files/neural_network_and_gaussian_process.pdf).

3.Diagnosing and forecasting Beijing PM2.5 (Python). 

4.Checkers programming project (Java). 
 -->


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
