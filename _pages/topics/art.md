---
layout: page
title: Art
permalink: /topics/art
created_lists:
  - image: /assets/img/art/awesome-modeling.png
    title: Awesome Modeling
    link: https://www.youtube.com/watch?v=MI4QEqt-xeM&list=PLu43en8_KcyKa3bMsu67PITBwhCqVBJBe
---

<div class='d-flex flex-row flex-wrap'>
  {% for item in page.created_lists %}
    <div class="col-md-4">
      <a href="{{ item.link }}">
        <img class="gallery-item-image" src="{{ item.image }}"/>
      </a>
      <div class="gallery-item-title">{{ item.title }}</div>
    </div>
  {% endfor %}
</div>