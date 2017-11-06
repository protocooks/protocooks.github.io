---
layout: page
show_meta: false
title: "Classes and Demos"
subheadline: "Learn to cook with Chef Frank"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/events/"
---
<ul>
    {% for post in site.categories.events %}
    <li>{{post.date | date: '%a, %b %e, %Y'}} - <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>