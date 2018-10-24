---
layout: page
title: Links
permalink: /links/
---

# Weekly Links

Below are a list of the weekly links:

{% for week in site.weekly_links %}
  <h2>
    <a href="{{ week.url }}">
      {{ week.name }}
    </a>
  </h2>
{% endfor %}
