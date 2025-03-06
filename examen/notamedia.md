---
layout: default
title: media
---

# Medias de alumnos
<ul>
{% for alumno in site.data.medias %}
    <li>{{ alumno.nombre }} {{ alumno.nota1 }} {{ alumno.nota2 }} {{ alumno.nota3 }} - MEDIAS {{ alumno.media }}</li>
{% endfor %}
</ul>