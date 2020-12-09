---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="https://dlingenbrink.github.io/files/lingenbrink-resume.pdf" target="_blank">Click here to see my current resume.</a>

Education
======
* B.S. in Mathematics, Harvey Mudd College, 2014
* M.S. in Operations Research, Cornell University, 2017
* Ph.D in Operations Research, Cornell University, 2019
  * Thesis: ["Information Design in Service Systems and Online Markets."](https://ecommons.cornell.edu/handle/1813/67405)  Advisor: [Krishnamurthy Iyer](https://people.orie.cornell.edu/kriyer/) 


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
