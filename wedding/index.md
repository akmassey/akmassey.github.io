---
layout: wedding
title: The Scoggins-Massey Wedding
---

# Welcome to our Wedding Website!

![Aaron and Allison at Jeremy and Meredith Kushner's Wedding][kushner]

Thanks for visiting!  We're happy to have you here.

# Updates

We hope to keep this website updated often.  If you're interested in
following along with any updates to the website, please [subscribe to
our feed](http://akmassey.com/wedding/feed.xml).  Here is a list of
previous updates:

<ul class="posts">
  {% for post in site.posts %}
    {% if post.category == 'wedding' %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="http://akmassey.com{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


[kushner]: /images/wedding/akm-acs-kushner-wedding.png
