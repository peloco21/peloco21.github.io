---
layout: default
title: Alumnos
---

# Lista de Alumnos
<ul>
{% for alumno in site.data.alumnos %}
    <li>{{ alumno.nombre }} {{ alumno.nota1 }} {{ alumno.nota2 }} {{ alumno.nota3 }}</li>
{% endfor %}
</ul>
