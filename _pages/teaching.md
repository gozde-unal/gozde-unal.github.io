---
layout: page
permalink: /teaching/
title: teaching
nav: true
nav_order: 5
---

{% assign sorted = site.data.teaching.courses | sort: "year" | reverse %} 
{% for course in sorted %} 
    {% include course.html course=course %} 
{% endfor %}
