---
image_path: /images/winter-2016/dsc00036jpg_26258551185_o.jpg
image_path: /images/winter-2016/dsc00049jpg_26258552775_o.jpg
image_path: /images/winter-2016/dsc00087jpg_26258554625_o.jpg
image_path: /images/winter-2016/dsc00110jpg_25985694170_o.jpg
image_path: /images/winter-2016/dsc00112jpg_26258546185_o.jpg
image_path: /images/winter-2016/dsc00196jpg_26166109572_o.jpg
image_path: /images/winter-2016/dsc09987jpg_25655864193_o.jpg
image_path: /images/winter-2016/dsc09990jpg_26258549235_o.jpg
---

<ul class="photo-gallery">
  {% for image in site.photo_gallery %}
    <li><img src="{{ image.image_path }}" alt=""/></li>
  {% endfor %}
</ul>
