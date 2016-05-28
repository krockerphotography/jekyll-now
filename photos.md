---
layout: page
title: Photos
permalink: /photos/
---

<section id="services">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading">At Your Service</h2>
        <hr class="primary">
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      {% for photo in site.photos %}
        <div class="col-lg-3 col-md-6 text-center">
          <div class="service-box">
            <img src="{{ photo.image_path }}" alt="{{ photo.title }}"/>
            <h3>{{ photo.title }}</h3>
            <p class="text-muted">{{ photo.content }}</p>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</section>
