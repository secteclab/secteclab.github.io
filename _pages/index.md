---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome
---

## What is it?

{% include components/intro.md %}

## How to use it

[Our blog]({{ site.baseurl }}{% link list/posts.html %}) enjoy it.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}
