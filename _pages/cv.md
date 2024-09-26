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
  * Languages: Python, R, SQL
  * Data processing: Pandas, Numpy, Spark, Matplotlib, ArcGIS, Google Earth Engine
  * Analytics: Scikit-learn, Torch, TensorFlow
  * Version control: Git
* Machine learning & statistics
  * Theorethical fundamentals
  * Algorithmic development
  * Experimental design
  * Robust evaluation and interpretation
  * Data processing pipelines
* Project management
* Academic Writing 
  

Publications
======
  <ul>{% for post in site.data.publications.main reversed %} 
    
    <div>{{post.title}}, {{post.authors}}, {{post.conference}}</div>
    <div class="links">
      {% if post.pdf %} 
      <a href="{{ post.pdf }}" class="btn" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if post.code %} 
      <a href="{{ post.code }}" class="btn" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if post.page %} 
      <a href="{{ post.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if post.bibtex %} 
      <a href="{{ post.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
    </div>
    <br>
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
  
