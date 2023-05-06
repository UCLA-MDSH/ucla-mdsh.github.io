---
layout: page
show_meta: false
title: "Curriculum"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: "Training Next-Generation Health Data Scientists"
    image_fullwidth: "fsph-students-900x500.jpg"
    
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Apply now! ›
#  style: alert

permalink: "/curriculum/"
---
<ul>
    {% for post in site.categories.curriculum %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
