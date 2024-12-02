---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}



Research Interests
======
Computational social science, network dynamics, misinformation, political communication, machine learning, and the societal impact of digital platforms. Special focus on analyzing large-scale data to understand youth experiences, civic discourse, and the broader implications for democracy.


Education
======
* Ph.D in Network Science, Northeastern University, 2026 (expected)
* M.Sc. in Social and Economic Data Science, University of Konstanz, 2021
* B.A. in Economics, Boğaziçi University, 2018

Research Experience
======
<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
  
  
Skills
======
* **Programming:** Python, R, SQL, AWS Cloud Computing  
* **Data Analysis:** Network analysis, quantitative research, data visualization  
  * Tools: Gephi, PySpark  
* **Languages:**  
  * Turkish (native), English (C2), Arabic (B2), German (B1) 


  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  

  

