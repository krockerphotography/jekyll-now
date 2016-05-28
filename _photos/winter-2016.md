---
layout: default
title: Winter 2016
image_path: /images/winter-2016/1.jpg
---

<h1>{{ page.title }}</h1>
<hr>

<div class="row">
{% for myimage in site.static_files %}<div class="col-md-4">{% if myimage.path contains 'img/970' %}<p>{{myimage.path}}</p>{% endif %}</div>{% endfor %}
</div>
