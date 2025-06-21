---
layout: archive
title: Proyectos
permalink: /proyectos/
author_profile: true
---

Aquí puedes ver algunos de los proyectos que he realizado recientemente:

{% for proyecto in site.proyectos %}
- [{{ proyecto.title }}]({{ proyecto.url }})
{% endfor %}
