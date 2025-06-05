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
I am currently a Global Research Assistant Professor at the Department of Data Science in the City University of Hong Kong (CityUHK). I received the B.S. degree from Huazhong University of Science and Technology (HUST) in 2016, and the M.S. degree from Institute of Automation Chinese Academy of Sciences (CASIA) in 2019. I received Ph.D degree in the School of Computer science, The University of Sydney (USYD) under the supervision of Prof. Dacheng Tao in 2024.


**Research Interests:** deep learning, quantum machine learning, distributed optimization.

## Research

{% for post in site.publications reversed %}
  {% if post.type == "recent" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=200&t=tt&d=1zD_YueupbltfMc7cHE7iVF8WMkLezziZpfEPbPu8dQ&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>