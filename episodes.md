---
layout: default
title: Episodes
---
<div class = "episodes">

<h2> Sonidos Escape </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "main" %}
        <li>
            <a href="{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>

<h2> Sonidos Extra</h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "extra" %}
        <li>
            <a href="{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>
</div> 