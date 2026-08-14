---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/cv.pdf" download>Download CV (PDF)</a></p>

<iframe src="{{ base_path }}/files/cv.pdf" width="100%" height="1000px" style="border: 1px solid #ddd;">
  This browser does not support inline PDFs. Please <a href="{{ base_path }}/files/cv.pdf">download the PDF</a> instead.
</iframe>

Education
======
* Ph.D. in Mechanical Engineering, Stanford University (in progress)
* B.S. in Mechanical Engineering, Penn State University, 2022 (with honors)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
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
