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
| Md Istiak Ahammed   | EERC 512           |  mahamm?@mtu.edu       | Environment perception          |
| Md Asifuzzaman   | EERC 512           |  masifu?@mtu.edu       | Robot design and bio sensing       |
| Tristan Hodgins   | EERC 512           |  tahodgin?@mtu.edu       | Underwater Vision          |

Masters Students
======

| Name            | Office                                   | Email       | Work               |
|-----------------|------------------------------------------|-------------|--------------------|


Alumni
======

| Name            | Degree/Year                                   | Company     | Email              |
|-----------------|-----------------------------------------------|-------------|--------------------|
| Benjamin Wittrup  | MS EE 2025           | Treetown Tech LLC        | bowittr?@mtu.edu          |
| Eli Gruhlke  | UG EE 2026           | California Eastern Laboratories (CEL)        |  ewgruhlk?@mtu.edu,eligruhlke?@gmail.com|
