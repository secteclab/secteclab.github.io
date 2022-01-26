---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome
---

## What is it?

{% include components/intro.md %}

## How to use it

[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}
