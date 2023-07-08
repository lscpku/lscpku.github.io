---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a PhD student at [LANCO](https://lancopku.github.io), School of Computer Science, Peking University. Advised by Prof. [Xu Sun](https://xusun.org)

Education
======
- PhD Student in Computer Science, Peking University, 2021.9 - Present
- BSc in Computer Science, Peking University, 2017.9 - 2021.6


Publications
======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication-single.html %}
{% endfor %}

<!-- {% for post in site.publications reversed %}
  - {% if post.venue %}({{ post.venue }}){% endif %} {{ post.title }}
{% endfor %} -->
