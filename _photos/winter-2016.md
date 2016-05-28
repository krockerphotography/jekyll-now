---
image: /images/winter-2016/dsc00036jpg_26258551185_o.jpg
title: Winter 2016
---

{% for image in site.images %}
 {% if image.extname == 'jpg' %}
  <img src="{{ file.url }}"/>
 {% endif %}
{% endfor %}
