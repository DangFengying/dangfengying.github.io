---
layout: archive
title: "Lab"
permalink: /lab/
author_profile: true
---

# Our Team

Welcome to our lab! Below are the profiles of the team members contributing to cutting-edge research in autonomous systems and robotics.

{% for member in site.data.team %}
  <div class="team-member">
    <img src="{{ '/images/' | append: member.image }}" alt="{{ member.name }}" class="team-member-image" />
    <h3>{{ member.name }}</h3>
    <p><strong>{{ member.role }}</strong></p>
    <p>{{ member.bio }}</p>
  </div>
{% endfor %}


Doctoral Students
======

| Name            | Office                                   | Email       | Work               |
|-----------------|------------------------------------------|-------------|--------------------|
| Md Istiak Ahammed   | EERC 501           |  mahamm?@mtu.edu       | Environment perception          |

Masters Students
======

| Name            | Office                                   | Email       | Work               |
|-----------------|------------------------------------------|-------------|--------------------|
| William Forney  | EERC 501           |  wbforne?@mtu.edu   | robot design          |
| Sharmilee Nowshin  | EERC 501        |  snowshi?@mtu.edu   | robot peception       |

Alumni
======

| Name            | Degree/Year                                   | Company     | Email              |
|-----------------|-----------------------------------------------|-------------|--------------------|
| Benjamin Wittrup  | MS EE 2025           | Treetown Tech LLC        | bowittr?@mtu.edu          |
