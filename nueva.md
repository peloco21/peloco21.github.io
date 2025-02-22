---
layout: page
title: Modelos de Coches
category: deportivos, eléctricos, sedán
lamine: coches
---

<ul>
  {% for coche in site.data.coches %}
    <li>
      {{ coche.marca }} {{ coche.modelo }} - {{ coche.tipo }} (Año: {{ coche.año }})
    </li>
  {% endfor %}
</ul>
