---
title: Ender 3
icon: fas fa-info-circle
order: 2
---

I used to have an Ender 3. I converted it into a switchwire.

* Marlin mechanical_gantry_align
* Klipper mechanical_gantry_align
* Afterburner/Stealthburner carriage addapter to fit voron parts to a stock ender 3 X axis.
* Switchwire Conversion
  * Modified magprobe

<p>Posts in category "basic" are:</p>

<ul>
  {% for post in site.categories.klipper %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
  
  
