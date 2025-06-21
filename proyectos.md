---
layout: default
title: Proyectos
---

# Lista de proyectos

<ul>
{% for proyecto in site.proyectos %}
  <li><a href="{{ proyecto.url }}">{{ proyecto.title }}</a></li>
{% endfor %}
</ul>