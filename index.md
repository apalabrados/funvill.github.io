---
layout: default
title: Home
---

This is the main page. This should have some introduction about what I do and some directions on where to go next..


## Projects

 - 2015 [Pocket Universe](/projects/pocketuniverse/) - Short description of this project

## Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
