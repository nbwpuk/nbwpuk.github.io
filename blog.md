---
layout: page
title:  "Blog"
---


<div class="row">
  {% for post in site.posts %}
    <div class="col-sm">
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </div>
  {% endfor %}
</div>