---
layout: page
title: Projects
permalink: /project/
image: 
---

프로젝트
<strong>AI 웹개발 과정 수료중 (2022.8 ~ 2023.01)</strong> 

{% if post.category.project %}
  {% for post in page.posts %}
    {% include article-content.html %}
  {% endfor %}
{% else %}s