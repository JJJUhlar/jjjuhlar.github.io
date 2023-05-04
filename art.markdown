---
layout: page
title: Photos
permalink: /art/
---

<div style="display: grid; column-gap: 5px; row-gap: 5px; grid-template-columns: repeat(3, 1fr);">

    {% for image in site.static_files %}
        {% if image.path contains 'images/art/' %}
            <a href="{{site.basurl}}{{image.path}}" target="_blank"><img src="{{site.basurl}}{{image.path}}" alt="image" /></a>
        {% endif %}
    {% endfor %}
</div>