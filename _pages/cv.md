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
* M.S. in Electrical Engineering, Ecole Centrale de Nantes, Nantes, France, 2010
* M.S. in Cognitive Science, Ecole Normale Superieure, Paris, France,  2012
* Ph.D in Theoretical Neuroscience and Machine Learning, Gatsby Unit (UCL), London, 2018

Work experience
======
* Since Feb 2018: Senior Machine Learning Researcher, Secondmind.ai
  * Conduct Machine learning research with a focus on Gaussian Processes for time-series and model-based reinforcement learning.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

