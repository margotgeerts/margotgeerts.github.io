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
* Ph.D in Business Economics, KU Leuven, 2025 (expected)
* M.S. in Business Information Systems Engineering, KU Leuven, 2021
* B.S. in Business Information Systems Engineering, KU Leuven, 2019

Work experience
======
* 2019 - 2021: Jobstudent financial assistant
  * imec
  * Duties includes: Updating internal documentation in SAP, Excel, and HTML
  * Supervisor: Financial controllers

* 2017 - 2019: Tutor
  * REBUS
  * Duties included: Tutoring first-year university students in economics, statistics and finance.


  
Skills
======
* Programming tools and frameworks
  * Languages: Python, R
  * Data processing: pandas, numpy, pyspark, matplotlib
  * Analytics: scikit-learn, pytorch
* Machine learning 
  * Algorithmic development
  * Experimental design
* Project management
* Academic Writing
  

Publications
======
  <ul>{% for post in site.data.publications.main reversed %}
    {% include post.title %}
    {% include post.authors %}
    {% include post.conference %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
