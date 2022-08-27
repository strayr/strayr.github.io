---
title: Voron
icon: fas fa-info-circle
order: 2
---

I have made some parts related to Voron printers.

* list
* all
* the
* repos

<ul>
  {% for post in site.categories.voron %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
  
  
