---
layout: page
title: Meet the People
nav_order: 3
permalink: /people/
---

## Creators
{% assign creators = site.staffers | where: 'role', 'creator' %}
{% for staffer in creators %}
{{ staffer }}
{% endfor %}

## Course Development Working Group
{% assign working_group = site.staffers | where: 'role', 'working group' %}
{% for staffer in working_group %}
{{ staffer }}
{% endfor %}
