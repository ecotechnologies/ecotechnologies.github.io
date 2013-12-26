---
title: articles
layout: default
---

<ul class="nav nav-tabs nav-justified">
  <li><a href="http://ecotechnologies.github.io/">Home</a></li>
  <li class="active"><a href="articles">Articles</a></li>
  <li><a href="videos">Videos</a></li>
  <li><a href="#">Tools</a></li>
  <li><a href="#">Suppliers</a></li>
  <li><a href="#">More ecotech resources</a></li>
</ul>

  {% for post in site.posts %}
		<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
  {% endfor %}
