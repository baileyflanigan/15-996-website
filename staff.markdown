---
layout: page
title: Meet the people
nav_order: 6
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

We would additionally like to thank the following people for lending us their expertise:
- Dr. Alexis Adams (Postdoctoral Teaching Consultant @ Eberly Center)
- Dr. Joanna Dickert (Assistant Dean for Educational Experience Assessment)
- Dr. Chad Hershock (Director of Faculty & Graduate Student Programs @ Eberly Center)
- Ashley Patton (Founding Director @ CS Pathways) 
- Dr. Maggie Hannan (Simon Initiative Associate Director for K-12 @ CS Pathways)
- Shernell Smith (Executive Director @ CMU Center for Diversity and Inclusion)
- Professor Geoff Kaufman (HCII)
- Dr. Pauline Rose Clance and Andra Gailis
- Dr. Daniel Ostick (Assistant Director for Student and Staff Development, Department of Resident Life, University of Maryland) and EDCP/HESI 470 (“Introduction to Student Personnel”)

