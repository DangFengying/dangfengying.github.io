---
layout: page
title: "Meet the Lab Members"
permalink: /lab/
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

Alumni
| Name            | Degree/Year                                   | Company | Email               |
|-----------------|-----------------------------------------------|-------------|--------------------|
| Benjamin Wittrup  | MS EE 2025           | Treetown Tech LLC        | bowittru@mtu.edu          |
