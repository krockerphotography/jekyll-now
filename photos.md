---
layout: page
title: Photography
permalink: /photography/
---

<div class="row">
{% for photo in site.photos %}
  <div class="col-md-4">
    <img class="img-responsive" src="{{ photo.image_path }}" alt="{{ photo.title }}"/>
  </div>
{% endfor %}
    
</div>
