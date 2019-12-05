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
* B.S. in Mathematics, Harvey Mudd College, 2014
* M.S. in Operations Research, Cornell University, 2017
* Ph.D in Operations Research, Cornell University, 2019 

Work experience
======
* Summer 2017: Research Scientist Internship (Amazon)
  *  Created quantile regression models to compare with black-box neural network

* Summer 2016: Machine Learning Internship (Bloomberg L.P.)
  *  Created language models using word2vec’s distributed word representations
  *  Modified word2vec to use a one-sided context window

* Summer 2014: Software Development Internship (Amazon)
  *  Fully integrated a new data source into Amazon’s outbound labor model
  *  Made UI and back-end tweaks to a internal labor model website

* Summer 2013: Project Management Internship (Microsoft)
  *  Developed algorithms for stopping outbound spam
  *  Created a spec for a new Outlook.com feature

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
