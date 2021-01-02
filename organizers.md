---
layout: page
title: Organization
---

## Organizing Committee

* Ioana Bica (University of Oxford)
* Marie Charpignon (MIT)
* Emma Pierson (Microsoft Research)
* Bryan Wilder* (Harvard University)

\*primary contact: bryan.wilder0@gmail.com

## Advisory Committee

* Jure Leskovec (Stanford University)
* Maimuna Majumder (Boston Children's Hospital and Harvard Medical School)
* Michael Mina (Harvard School of Public Health)
* Balaraman Ravindran (IIT Madras)
* James Zou (Stanford University)



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


