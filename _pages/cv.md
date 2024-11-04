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
* *2021.09 - now*, Ph.D. Candidate, University of Science and Technology of China (USTC),
* *2017.09 - 2021.07*, B.E., University of Science and Technology of China (USTC).

Work experience
======
* *2022.11 - 2023.08*: ByteDance - AI LAB
  * Internship
  * Duties includes:
      * Entity linking in news;
      * Encyclopedia data cleaning for LLM;
      * Encyclopedia LLM Fine-tuning for QA;

Skills
======
* Python, C/C++
* Pytorch, PyG
* Linux
* Git(Github), Flask, Django

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

