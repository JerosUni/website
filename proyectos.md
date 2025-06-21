---
layout: default
title: Proyectos
---

# Lista de proyectos

<ul>
{% for proyecto in site.proyectos %}
  <li><strong>{{ proyecto.title }}</strong>: {{ proyecto.content | markdownify }}</li>
{% endfor %}
</ul>