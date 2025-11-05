---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

# Latest Blog Posts

Welcome to my blog about Quantum Systems, Optics, and Computing.

{% include base_path %}
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
