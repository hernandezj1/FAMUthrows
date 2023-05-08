---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Coaches


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
