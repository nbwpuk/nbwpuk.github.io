---
layout: page
title:  "Blog"
---


<div class="row">
  {% for post in site.posts %}
    <div class="col-sm">
      <a class="btn btn-primary" href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </div>
  {% endfor %}
</div>