---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h3><a href="https://arxiv.org/abs/2207.05617" target="_blank">Mechanizing Refinement Types</a></h3>

**Michael H. Borkowski**, Niki Vazou, and Ranjit Jhala. To appear in *51st ACM SIGPLAN Symposium on Principles of Programming Languages (POPL 2024)*


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
