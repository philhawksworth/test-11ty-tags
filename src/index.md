---
title: Testing property overrides
layout: layouts/base.njk
---

## Pages in the "post" collection

This should show all the post files listed in the `/posts` directory.

<ul>
{% for page in collections.post %}
  <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{% endfor %}
</ul>


## Pages which had hopefully been tagged "post"

Manually listed for convenience

<ul>
  <li><a href="/posts/an-untagged-post/">An untagged post</a></li>
  <li><a href="/posts/a-tagged-post/">A tagged post</a></li>
</ul>
