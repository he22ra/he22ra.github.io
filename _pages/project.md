---
layout: default
title: Project
permalink: /project/
---

<div class="container">
    <div class="post-title-box">
      <div class="row">
        <div class="col col-10 push-1 col-11 push-t-1 col-m-12 push-m-0">
          <h1 class="post-title"><span>{{ page.title }}</span></h1>
        </div>
      </div>
    </div>
  </div>
  

    {% for post in site.posts %}
      {% if post.tags contains 'project' %}

          {% include article-content.html %}

      {% endif %}
    {% endfor %}

  