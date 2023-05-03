---
layout: page
title: Photos
permalink: /art/
---

<div style="display: grid; column-gap: 5px; row-gap: 5px; grid: repeat(3, 100px); grid-auto-flow: row;">
    {% for image in site.static_files %}
        {% if image.path contains 'images/art/' %}
            <img src="{{site.basurl}}{{image.path}}" alt="image" />
        {% endif %}
    {% endfor %}
</div>