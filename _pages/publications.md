---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### Peer-Reviewed

Korinna Lindemann and Lukas F. Stoetzer. The effect of televised candidate debates on the support for political parties. *[Electoral Studies](https://www.sciencedirect.com/science/article/abs/pii/S0261379420301220)*, 9, 102243, 2021.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
