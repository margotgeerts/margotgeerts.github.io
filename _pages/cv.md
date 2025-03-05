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
* 2021 - 2025: PhD Researcher
  * Research Centre for Information Systems Engineering (LIRIS), KU Leuven
  * Conducting research at the intersection of Machine Learning, geospatial data, and real estate analytics, focusing on model performance, interpretability, and uncertainty quantification.
  * Developed custom ML models for structured and unstructured data, using Python libraries such as PyTorch, TensorFlow, and Scikit-learn.
  * Collaborated with Statistics Denmark through the European Data Science Exchange Program and industry partners to apply ML solutions to real-world business challenges.
  * Published peer-reviewed research in international journals and conferences.
  * Guided master thesis projects and taught lectures in analytics.
    
* 2021 - 2023: Machine Learning Researcher
  * Fednot
  * Collaborated with a team of data scientists and machine learning engineers to apply AI for real estate.
  * Finetuned convolutional neural networks to classify Google Street View images of real estate properties.
  * Improved accuracy and interpretability of real estate price prediction models by tailoring tree-based algorithms to geospatial input data.
  * Researched the efficacy of location-informed real estate networks to predict real estate prices with graph neural networks.
    
* 2019 - 2021: Jobstudent financial assistant
  * imec
  * Performed administrative tasks and updated internal documentation in SAP, Excel, and HTML

* 2017 - 2019: Tutor
  * REBUS
  * Tutored first-year university students in economics, statistics and finance.


  
Skills
======
* Programming tools and frameworks
  * Languages: Python, R, SQL
  * Data processing: Pandas, Numpy, Spark, Matplotlib, ArcGIS, Google Earth Engine
  * Analytics: Scikit-learn, Torch, HuggingFace
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
    
    <div><a href="{{ post.pdf }}">{{ post.title }}</a>, {{post.authors}}, <em>{{post.conference}}</em> </div>
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
  
