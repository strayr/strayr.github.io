---
title: Klipper
icon: fas fa-info-circle
order: 2
---

I run klipper on my printers, and maintain some macros for it.

* [strayr-k-macros](https://github.com/strayr/strayr-k-macros)

<ul>
  {% for post in site.categories.klipper %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
  
  
