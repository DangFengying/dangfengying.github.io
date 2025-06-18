---
layout: archive
title: "Lab"
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
| BBBBBBB   | EERC 501           |  BBBBBBB@mtu.edu       | BBBBBBB          |

Masters Students
======

| Name            | Office                                   | Email       | Work               |
|-----------------|------------------------------------------|-------------|--------------------|
| B  | EERC 501           |  @mtu.edu       | b          |

Alumni
======

| Name            | Degree/Year                                   | Company     | Email              |
|-----------------|-----------------------------------------------|-------------|--------------------|
| Benjamin Wittrup  | MS EE 2025           | Treetown Tech LLC        | bowittru@mtu.edu          |
