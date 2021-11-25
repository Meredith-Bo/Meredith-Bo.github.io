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
* B.Sc. in Statistics, University of California, Los Angeles, June 2021 
* Ph.D in Statistics, University of California, Berkeley, August 2021 - Present

Work experience
======
## Undergraduate/Graduate Student Researcher

### Los Alamos National Laboratory, June 2016 - Present

  * Utilized Bayesian Multivariate Adaptive Regression Splines (BMARS) to develop a robust model with non-Gaussian likelihoods (R Package [TBASS](https://github.com/aashen12/TBASS), 2020).
  
  * Forecasting spread of mosquito-borne diseases using Hawkes point process models and other spatial methods.
  
## Undergraduate Student Researcher, August 2020 - July 2021

### UCLA Department of Statistics

  * Used Hawkes and recursive Hawkes point process models to forecast Ebola spread in the Democratic Republic of the Congo. Advised by Professor [Rick Schoenberg](http://www.stat.ucla.edu/~frederic/).



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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
