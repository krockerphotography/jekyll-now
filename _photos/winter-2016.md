---
layout: default
title: Winter 2016
permalink: /photography/winter-2016/
portfolio:
  - image_path: /images/winter-2016/dsc00036jpg_26258551185_o.jpg
    category: Web Design
    project: Apple
    url: http://apple.com

---
<section class="bg-dark">
  <div class="text-center">
    <h1>Portfolio</h1>
  </div>
</section>

<section class="no-padding" id="portfolio">
  <div class="container-fluid">
    <div class="row no-gutter">
      {% for item in page.portfolio %}
      <div class="col-lg-4 col-sm-6">
        <a href="{{ item.url }}" class="portfolio-box">
          <img src="{{ item.image_path }}" class="img-responsive" alt="{{ item.project }}">
          <div class="portfolio-box-caption">
            <div class="portfolio-box-caption-content">
              <div class="project-category text-faded">
                {{ item.category }}
              </div>
              <div class="project-name">
                {{ item.project }}
              </div>
            </div>
          </div>
        </a>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
