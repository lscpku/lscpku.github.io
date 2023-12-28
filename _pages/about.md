---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I am a PhD student at [LANCO](https://lancopku.github.io), Institute of Computational Linguistics (National Key Laboratory for Multimedia Information Processing), School of Computer Science, Peking University. My advisor is Prof. [Xu Sun](https://xusun26.github.io). My research interests lie in natural language processing and multimodal machine learning.

Education
=========

- PhD Student in Computer Science, Peking University, 2021.9 - Present
- BSc in Computer Science, Peking University, 2017.9 - 2021.7

Publications
============

{% include base_path %}

<ul>
{% for post in site.publications reversed %}
  {% include publication-single.html %}
{% endfor %}
</ul>

<!-- {% for post in site.publications reversed %}
  - {% if post.venue %}({{ post.venue }}){% endif %} {{ post.title }}
{% endfor %} -->
