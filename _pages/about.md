---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /home/
twitter-color: "#55acee"
github-color: "#171516"
blogger-color: "#F37100"
---
I received the B.S. degree from Huazhong University of Science and Technology (HUST) in 2016, and the M.S. degree from Institute of Automation Chinese Academy of Sciences (CASIA) in 2019. I received Ph.D degree in the School of Computer science, The University of Sydney under the supervision of Prof. Dacheng Tao in 2024.


**Research Interests:** deep learning, quantum machine learning, distributed optimization.

## Research

{% for post in site.publications reversed %}
  {% if post.type == "recent" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}