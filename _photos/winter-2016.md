---
title: Winter 2016
path: winter-2016
---

{% for image in site.static_files %}
    {% if image.path contains '_photos/winter-2016' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
