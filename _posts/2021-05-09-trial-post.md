---
layout: single
title:  "Welcome to Jekyll!"
header:
  teaser: /assets/images/unsplash-gallery-image-3-th.jpg
categories: 
  - Jekyll
tags:
  - edge case
---

{% capture fig_img %}
![Foo]({{ "/assets/images/unsplash-gallery-image-3.jpg" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Photo from Unsplash.</figcaption>
</figure>

# Welcome to my first blogpost

**Hello world**, this is my first Jekyll blog post.

I hope you like it!