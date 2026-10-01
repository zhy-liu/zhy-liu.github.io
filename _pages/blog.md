---
layout: archive
permalink: /blog/
title: "Blog"
author_profile: true
---

{% assign articles = site.blog | sort: "title" %}
{% for post in articles %}
  {% include archive-single.html %}
{% endfor %}
