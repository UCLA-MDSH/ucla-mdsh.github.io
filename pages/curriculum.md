---
layout: page
show_meta: false
title: "Curriculum"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: "Training Next-Generation Health Data Scientists"
    image_fullwidth: "fsph-students-900x500.jpg"
    
callforaction:
 url: /apply/
 text: Apply Now ›
 style: alert

permalink: "/curriculum/"
---

Our students benefit from a cohort-based, cutting-edge curriculum administered by the top professors in the field, offering unparalleled opportunities in the dynamic intersection of data science and healthcare.

<ul>
    {% for post in site.categories.curriculum %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
