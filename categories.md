<<<<<<< HEAD
---
layout: default
permalink: /categories
title: Categories
---
{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}">
        <h2>{{ category_name }}</h2>

        <ul>
          {% for post in site.categories[category_name] %}
            <li><a class="archive-link" href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
          {% endfor %}
        </ul>
    </div>
  </div>
=======
---
layout: default
permalink: /categories
title: Categories
---
{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}">
        <h2>{{ category_name }}</h2>

        <ul>
          {% for post in site.categories[category_name] %}
            <li><a class="archive-link" href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
          {% endfor %}
        </ul>
    </div>
  </div>
>>>>>>> b5142198b07d7d737d45e8b7abed64a9c1740334
{% endfor %}