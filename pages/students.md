---
layout: page
show_meta: false
title: "Students"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: "Training Next-Generation Health Data Scientists"
    image_fullwidth: "jay-xu-tom-belin-900-400.jpg"
permalink: "/students/"
---
<ul>
    {% for post in site.categories.students %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
