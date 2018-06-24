---
title: Testing property overrides
layout: layouts/base.njk
---

## Post pages

This should show all the post files listed in the `/posts` directory.

<ul>
{% for page in collections.post %}
  <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>
