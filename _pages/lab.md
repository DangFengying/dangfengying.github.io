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


| Role            | Course                                        | Institution | Term               |
|-----------------|-----------------------------------------------|-------------|--------------------|
| Lecturer  | EE 5522 - Digital Image Processing           | MTU         | Fall 2025          |
| Lecturer  | EE 3261 - Linear Systems and Control         | MTU         | Spring 2025        |
| Lecturer  | EE 5522 - Digital Image Processing           | MTU         | Fall 2024          |
| Guest Lecturer  | ME 851 - Linear Systems and Control           | MSU         | Fall 2022          |
| Guest Lecturer  | ECE884 - Neural Networks and Deep Learning    | MSU         | Fall 2022          |
| Guest Lecturer  | ECE 521 - Linear Systems and Control          | GMU         | Spring 2020        |
| Teaching Assistant | ECE 521 - Linear Systems and Control        | GMU         | Fall 2019          |
| Teaching Assistant | ECE 421 - Classical Systems and Control Theory | GMU     | 2018-2020          |
| Teaching Assistant | ECE 320 - Signals and Systems II           | GMU         | Spring 2018        |
| Teaching Assistant | ENGR107 - Introduction to Engineering       | GMU         | Fall 2018, Spring 2019 |

Doctoral Students
======
| Name            | Office                                   | Email       | Work               |
|-----------------|------------------------------------------|-------------|--------------------|
| BBBBBBB   | EERC 501           |  BBBBBBB@mtu.edu       | BBBBBBB          |
| Lecturer  | EE 5522 - Digital Image Processing           | MTU         | Fall 2025          |

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
