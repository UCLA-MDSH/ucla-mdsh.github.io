---
layout: page
show_meta: false
title: "Admission"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: "Training Next-Generation Health Data Scientists"
    image_fullwidth: "dickson-court-birdview-1200-900.jpeg"
    
callforaction:
 url: /apply/
 text: Apply Now ›
 style: alert
  
permalink: "/admission/"
---

Each fall a new cohort of MDSH students enters this two-year program. For details about admissions, we recommend carefully reviewing these four pages:

<ul>
    {% for post in site.categories.admission %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}

<li><a href="{{ site.url }}{{ site.baseurl }}/FAQ/">FAQ</a></li>
</ul>
