---
title: Ender 3 Switchwire
icon: fas fa-info-circle
order: 2
---

I used to have an Ender 3. I converted it into a switchwire. I maintain the [Switchwire Conversion Mod Registry](https://github.com/SW-Conversion/mod-regisistry).

<ul>
  {% for post in site.categories.klipper %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

### To document
* Afterburner/Stealthburner carriage addapter to fit voron parts to a stock ender 3 X axis.
* Switchwire Conversion
  * Modified magprobe
  
  
