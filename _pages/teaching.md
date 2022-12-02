---
layout: page
permalink: /teaching/
title: teaching
nav: true
nav_order: 5
---

{% for course in site.data.teaching.courses %} 
    {% include course.html course=course %} 
{% endfor %}
