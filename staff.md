---
layout: page
title: 🤝 Team
description: A listing of all the course staff members.
nav_order: 6
---

# 🤝 Team

## Instructor


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Staff

{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

{% assign staff = site.staffers | where: 'role', 'Tutor' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>
