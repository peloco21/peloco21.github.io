---
layout: page
title: Modelos de Coches
category: deportivos, eléctricos, sedán
coches: coches
---

<ul>
  {% for coche in site.data.coches %}
    <li>
      {{ coche.marca }} {{ coche.modelo }} - {{ coche.tipo }}
    </li>
  {% endfor %}
</ul>
