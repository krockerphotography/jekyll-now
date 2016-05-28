---
layout: default
title: Winter 2016
image_path: /images/winter-2016/1.jpg
---

{% for image in site.static_files %}
    {% if image.path contains 'images/winter-2016' %}
        <img src="{{ site.baseurl }}{{ image.path }}.jpg" alt="image" />
    {% endif %}
{% endfor %}
