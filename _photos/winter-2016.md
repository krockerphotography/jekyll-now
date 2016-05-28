---
layout: default
title: Winter 2016
image_path: /images/winter-2016/1.jpg
---

<div class="row">
{% for myimage in site.static_files %}{% if myimage.path contains 'images/winter-2016' %}<div class="col-md-4"><img src="{{myimage.path}}"></div>{% endif %}{% endfor %}
</div>
