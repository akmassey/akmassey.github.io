---
layout: wedding-update
title: Scoggins-Massey Wedding Updates
---

# Updates

If you're interested in following along with any updates to the website,
please [subscribe to our feed](http://akmassey.com/wedding/feed.xml).
Here is a list of previous updates:

<ul class="posts">
  {% for post in site.posts %}
    {% if post.category == 'wedding' %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="http://localhost:4000{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
