---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Maryland PSSG Group, 2030 (Expected)
* M.S.E in Computer & Information Science Concentration in Systems, University of Pennsylvania, 2026
* B.S in Computer Science Minor in Computer Engineering, Pennsylvania State University, 2024

Work experience
======
* AI/ML Research Engineer, Lockheed Martin Enterprise Operations
  * Applied AI Mission Management Team
  * Presented our Team's Work at the MORS conference

* Associate Software Engineer, Lockheed Martin
  * Advanced Extremely High Frequency Team
  * Full Stack SWE focused on backend C# development
  
Skills
======
* C#
* Software Testing
* C
* Python
* Machine Learning
* Computer Networking
* Graph Neural Networks
* Natural Language Processing
* Computer Vision

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
