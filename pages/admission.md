---
layout: page
show_meta: false
title: "Admission"
# subheadline: "Layouts of Feeling Responsive"
header:
    title: "Training Next-Generation Health Data Scientists"
    image_fullwidth: "dickson-court-birdview-1200-900.jpeg"
permalink: "/admission/"
---
<ul>
    {% for post in site.categories.admission %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
