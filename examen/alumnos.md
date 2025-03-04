---
layout: default
title: Alumnos
---

# Lista de Alumnos
<ul>
{% for alumno in site.data.alumnos %}
    <li>{{ alumno.nombre }} {{ alumno.apellidos }}</li>
{% endfor %}
</ul>
