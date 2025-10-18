---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: true
---

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
    <p><small>Published on {{ post.date | date: "%B %d, %Y" }}</small></p>
  </article>
{% endfor %}