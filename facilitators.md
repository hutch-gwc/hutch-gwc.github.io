---
layout: page
title: Facilitators
permalink: /facilitators/
---

Hopefully this is page where we can see information about facilitators

{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
