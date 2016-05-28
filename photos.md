---
layout: page
title: Photos
permalink: /photos/
---

{% for myimage in site.static_files %}{% if myimage.path contains '_photos/winter-2016' %}<p>{{myimage.path}}</p>{% endif %}{% endfor %}
