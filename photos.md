---
layout: page
title: Photos
permalink: /photos/
---

<ul class="photo-gallery">
{% for image in site.images %}
     {% if image.extname == 'jpg' %}
         <li><img src="{{ site.baseurl }}/_photos/winter-2016/{{ file.url }}" /></li>
     {% endif %}
{% endfor %}
</ul>
