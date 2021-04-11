---
layout: page
title:  "Blog"
---


<div class="row">
  {% for post in site.posts %}
    <div class="col-sm">
      <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
      {{ post.excerpt | markdownify | strip_html | truncatewords: 50 }}
    </div>
  {% endfor %}
</div>