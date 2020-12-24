---
layout: archive
title: "Publicações"
permalink: /publicações/
author_profile: true
---

{% include base_path %}

Você pode achar os artigos que já publiquei no meu <a href="https://www.researchgate.net/profile/Hugo_Azevedo5">perfil do ResearchGate</a>.


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}