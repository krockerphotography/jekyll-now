---
layout: default
title: Winter 2016
image_path: /images/winter-2016/1.jpg
---

{% for myimage in site.static_files %}{% if myimage.path contains 'images/winter-2016' %}<p><img src="{{myimage.path}}"></p>{% endif %}{% endfor %}
