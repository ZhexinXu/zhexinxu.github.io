---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work Experience
======
* Senior Data Scientist Intern, IBM, 2022

Education
======
* PhD, Brain & Cognitive Sciences, jointly in Computer Science, University of Rochester, 2023

Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
======
  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======

  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
