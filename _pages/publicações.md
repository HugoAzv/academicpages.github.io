---
layout: archive
title: "Publicações"
permalink: /publicações/
author_profile: true
---

{% if author.researchgate %}
  Você pode achar os artigos que já publiquei no meu <u><a href="{{author.researchgate}}">perfil do ResearchGate</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}