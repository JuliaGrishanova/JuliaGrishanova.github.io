---
title: "Examen"
layout: default
permalink: /examen/
author_profile: true
---

# nota



<ul>
  {% for ex in site.examen %}
    <li>
      <a href="{{ ex.url }}">{{ ex.title }}</a>
    </li>
  {% endfor %}
</ul>

[Regresar a Home](/)
