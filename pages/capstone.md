---
layout: page
show_meta: false
title: "MDSH Capstone"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: ""
    image_fullwidth: "capstone1.jpeg"
    
callforaction:
 url: /apply/
 text: Apply Now ›
 style: alert

permalink: "/capstone/"
---

The purpose of the Capstone Project is for second-year MDSH students to apply theoretical knowledge acquired during the Master of Health Data Science (MDSH) program to a project involving actual biomedical, public health, or business data in a realistic setting. Students form teams of 5 or 6 and collaborate with a partner organization to solve a business or healthcare question identified by the partner. Each year, students and industry partners participate in the MDSH Summit, which features student project presentations and plenary talks from industry leaders.

<ul>
    {% for post in site.categories.capstone %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
