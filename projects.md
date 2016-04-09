---
layout: page
title: Projects
permalink: /projects/
---

<div class="posts">
  {% for projects in site.projects %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{projects.url }}">{{ projects.title }}</a></h1>

      <div class="entry">
        {{ projects.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ project.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>