---
layout: page
title: AI for Public Health
use-site-title: true
---

# Overview

The COVID-19 pandemic has cast a spotlight on the importance of public health. Even beyond this current emergency, public health is an essential component of population-level wellbeing. Topics such as infectious disease surveillance and control, preventative health, behavioral and mental health, maternal and child wellbeing, and more all play a crucial role in society. Moreover, a range of applications in public health benefit from careful use of data to uncover outbreak dynamics, learn patterns of behavior, optimize the design of interventions, and more. The science of machine learning in a public health context is still rapidly developing, and our aim is to build a community encompassing researchers based in both machine learning and public health to address these shared questions.


| ------------- |:-------------:|
| **Submission** | February 26th, 2021   |
| **Notification** | March 26th, 2021 |


<hr>

# Speakers and Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
  {% for p in site.data.speakers %}
  {% if forloop.index<=4 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizing Committee

* Ioana Bica (University of Oxford)
* Marie Charpignon (MIT)
* Emma Pierson (Microsoft Research)
* Bryan Wilder* (Harvard University)

\*primary contact: bryan.wilder0@gmail.com

# Advisory Committee

* Jure Leskovec (Stanford University)
* Maimuna Majumder (Boston Children's Hospital and Harvard Medical School)
* Michael Mina (Harvard School of Public Health)
* Balaraman Ravindran (IIT Madras)
* James Zou (Stanford University)

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>
<hr>




<div class="container" style="margin-bottom: 10px;"></div>

<hr>

