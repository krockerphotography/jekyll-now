---
layout: page
title: Photography
permalink: /photography/
---

  <div class="container">
    <div class="row">
      {% for photo in site.photos %}
        <div class="col-lg-3 col-md-6 text-center">
          <div class="service-box">
            <img class="img-responsive src="{{ photo.image_path }}" alt="{{ photo.title }}"/>
            <h3><a href="{{ photo.url }}">{{ photo.title }}</a></h3>
            <p class="text-muted">{{ photo.content }}</p>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>

