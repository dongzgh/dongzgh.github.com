---
title: Video
permalink: /views/video
---

<div class='d-flex flex-row flex-wrap'>
  {% assign pages = site.pages | where: 'tags', 'video' %}
  {% for page in pages %}
  <div class="col-3">
    <a href="{{ page.permalink }}">
      <img class="gallery-item-image" src="{{ page.image }}"/>
    </a>
  </div>
  {% endfor %}
</div>
