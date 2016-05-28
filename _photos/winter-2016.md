---
layout: default
title: Winter 2016
image_path: /images/winter-2016/1.jpg
---

<h1>{{ page.title }}</h1>
<hr>

<div class="row">
{% for myimage in site.static_files %}<div class="col-lg-3 thumb">{% if myimage.path contains 'images/winter-2016' %}<img class="img-responsive" src="{{myimage.path}}">{% endif %}</div>{% endfor %}
</div>
