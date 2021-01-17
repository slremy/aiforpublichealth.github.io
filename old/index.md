---
layout: default
title: Home
---
# AI for Public Health

The COVID-19 pandemic has cast a spotlight on the importance of public health. Even beyond this current emergency, public health is an essential component of population-level wellbeing. Topics such as infectious disease surveillance and control, preventative health, behavioral and mental health, maternal and child wellbeing, and more all play a crucial role in society. Moreover, a range of applications in public health benefit from careful use of data to uncover outbreak dynamics, learn patterns of behavior, optimize the design of interventions, and more. The science of machine learning in a public health context is still rapidly developing, and our aim is to build a community encompassing researchers based in both machine learning and public health to address these shared questions.

The (fully virtual) workshop will be head at [ICLR 2021](https://iclr.cc/Conferences/2021/) on May 8 2021.


<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>


