---
layout: page
title: Blog
---
A collection of writings on product management, design, technology, startups, and brands. 

{% for post in site.posts %}
 * [ {{ post.title }} ]({{ post.url }})  {{ post.date | date_to_string }}{% endfor %}

