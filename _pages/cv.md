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
* Ph.D in Engineering (Materials Innovation), University of Tsukuba, 2024
* M.S. in Chemistry (Physical Chemistry and Chemical Physics), University of Bordeaux, 2020
* B.S. in Chemistry, Colorado School of Mines, 2016

Work experience
======
* April 2024 - : Postdoctoral Researcher
  * AIST, OPERANDO OIL
  * Duties includes: Development of time resolved x-ray measurement techniques.
  * Supervisor: Dr. Kazuhiro Mio
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
-->
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conference Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->  
<!--Service and leadership
======
* Currently signed in to 43 different slack teams
-->